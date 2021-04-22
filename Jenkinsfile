pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'apt-get update'
                sh 'apt-get upgrade'
                sh 'pip install python'
                sh 'python hello.py'
            }
        }
    }
}