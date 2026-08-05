pipeline {
    agent any
    stages {
        stage('Build Stage') {
            steps {
                sh '''
                echo "Build Successful" > report.txt
                '''
                sh '''
                echo "Build stage 2 Successful" > report.txt
                '''
            }
        }
        stage('Test Stage') {
            steps {
                sh '''
                echo "Test Successful" > report.txt
                '''
            }
        }
        stage('Deploy Stage') {
            steps {
                sh '''
                echo "Deploy Successful" > deploy.txt
                '''
            }
        }
        
    }
    post {
        always {
            echo "pipeline finished"
        }
    }
}
