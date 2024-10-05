pipeline {
    agent any
    tools {
        nodejs '20.18.0'
    }
    stages {
        stage('Build'){
            steps {
                sh 'npm install'
            }
        }
    }
}