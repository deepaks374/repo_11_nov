pipeline {

    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy to Production') {
            when {
                branch 'main'
            }
            
            steps {
                echo 'Deploying to production...'
                // Production deployment script goes here
            }
        }
    }

}
