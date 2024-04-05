pipeline { 
    agent {
        label 'ws'
    }
    stages {
        stage('Lint Checks') {
            steps {
                sh "echo Perform Lint Checker"
                //sh "mvn checkstyle:check || true"

            }
        }
        stage('Static Code Analysis') {
            steps {
                sh "echo Static Checks ...."
            }
        }
    }
}