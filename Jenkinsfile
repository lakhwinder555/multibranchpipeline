pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                echo 'lakhwinder'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            when {
                branch 'staging'
            }
            steps {
                echo 'Deploying...'
                
            }
        }
    }
}
