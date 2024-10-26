pipeline {
    agent any
    stages {
        stage('Build project') {
            steps {
                sh 'dotnet build'
            }
        }
        stage('Execute tests') {
            steps {
                sh 'dotnet test'
            }
        }
    }
}
