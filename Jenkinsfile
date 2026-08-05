pipeline {
    agent any
    environment {
        PROJECT_NAME = "Employee Portal"
    }
    
    stages {
        stage('ProjectName') {
            steps {
                echo "Project : ${PROJECT_NAME}"
                echo "BUILD_NUMBER : ${BUILD_NUMBER}"
                echo "JOB_NAME : ${JOB_NAME}"
                echo "BUILD_ID : ${BUILD_ID}"
                echo "WORKSPACE : ${WORKSPACE}"
                echo "BUILD_URL : ${BUILD_URL}"
                echo "NODE_NAME : ${NODE_NAME}"
                

            }
        }
    }
}
