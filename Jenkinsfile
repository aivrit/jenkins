pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'whoami'
            }
        stage('build') {
            agent { docker 'python:3.5.1' }
            steps {
                sh 'python --version'
            }
        }
    }
}
