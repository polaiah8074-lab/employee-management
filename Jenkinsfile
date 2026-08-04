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
        stage('DisplayVersion') {
            steps {
                echo "Version : ${params.VERSION}"
            }
        }
    }
}
