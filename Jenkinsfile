pipeline {
    agent any 
    
    environment {
        Dev = 'SeniorDev'
    }
    
    stages {
        stage('Build') {
            steps {
                echo "Building"
                echo "Samuel Persis Hosted Me In His Place But I don't Know"
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing'
                echo "I love programming"
            }
        }
        stage('Deploy') {
            when {
                environment name: 'Dev', value: 'SeniorDev'
            }
            steps {
                echo "Deploying"
                echo "Done!"
            }
        }
        stage('Prod') {
            steps {
                echo "I got it!"
            }
        }
    }
}
