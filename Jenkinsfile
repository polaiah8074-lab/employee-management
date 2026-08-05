pipeline {
    agent any
    stages {
        stage('Create Report') {
            steps {
                sh '''
                echo "Build Successful" > report.txt
                '''
            }
        }
    }
    post {
        success {
            archiveArtifacts artifacts: 'report.txt'
        }
    }
}
