pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                echo 'Compiling source code...'
                echo 'Build completed!'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Running tests...'
                echo 'All tests passed!'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                echo 'Deployment successful!'
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline successful!'
        }
        failure {
            echo 'Pipeline FAILED!'
        }
    }
}
