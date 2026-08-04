pipeline {
    agent any
    parameters {
        string (
            name: 'VERSION',
            defaultValue: '1.0.6',
            description: 'App Version' 
        )
    }
    stages {
        stage('DisplayEnvironment') {
            steps {
                echo "Select Environment : ${params.ENVIRONMENT}"
            }
        }
    }
}
