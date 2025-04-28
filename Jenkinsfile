pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo 'Building with Maven' }
        }
        stage('Unit Tests') {
            steps { echo 'Running JUnit tests' }
        }
        stage('Integration Tests') {
            steps { echo 'Running TestNG tests' }
        }
        stage('Code Analysis') {
            steps { echo 'Scanning with SonarQube' }
        }
        stage('Security Scan') {
            steps { echo 'Running OWASP Dependency-Check' }
        }
        stage('Deploy to Staging') {
            steps { echo 'Deploying to AWS EC2 staging' }
        }
        stage('Deploy to Production') {
            steps { echo 'Deploying to AWS EC2 production' }
        }
    }
}
