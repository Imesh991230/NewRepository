pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the code using Maven...'
                // Replace with actual Maven build command
            }
        }
        stage('Unit Tests') {
            steps {
                echo 'Running unit tests...'
                // Replace with actual unit test command (e.g., JUnit)
            }
        }
        stage('Integration Tests') {
            steps {
                echo 'Running integration tests...'
                // Replace with actual integration test command (e.g., Postman/Newman)
            }
        }
        stage('Static Code Analysis') {
            steps {
                echo 'Analyzing the code using SonarQube...'
                // Replace with actual SonarQube analysis command
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Performing security scan...'
                // Replace with actual security scan command (e.g., OWASP Dependency-Check)
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging server...'
                // Replace with actual deployment command (e.g., Ansible or Docker)
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging environment...'
                // Replace with actual integration tests on staging command (e.g., Selenium)
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production server...'
                // Replace with actual deployment to production command (e.g., Ansible or Docker)
            }
        }
    }

    post {
        always {
            mail body: 'Pipeline completed. All stages checked successfully. Check console output for details.',
                to: 'imeshmedagama99@gmail.com',
                subject: 'Jenkins Pipeline Status'
        }
    }
}
