pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                bat 'echo Build - Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                bat 'echo Unit and Integration Tests - JUnit and Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                bat 'echo Code Analysis - SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                bat 'echo Security Scan - OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                bat 'echo Deploy to Staging - AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                bat 'echo Integration Tests on Staging - Postman/Newman'
            }
        }

        stage('Deploy to Production') {
            steps {
                bat 'echo Deploy to Production - AWS CodeDeploy'
            }
        }
    }
}
