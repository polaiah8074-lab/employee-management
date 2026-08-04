pipeline {
    agent any
    parameters {
        choice (
            name: 'ENVIRONMENT',
            choices: ['development','testing','production'],
            description: 'choose environment' 
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
