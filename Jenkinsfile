pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
            sh 'echo checkout'
            checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/jank10/DevOpsDemo']])
            }
            }
            stage('Test') {
            steps {
            sh 'echo test'
            }
            }
            stage('Deploy') {
            steps {
            sh 'echo deploy'
            }
        }
    }
}
