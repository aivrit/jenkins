pipeline {
    agent {
        node {
            any
            customWorkspace '/var/cmp/infrastructure'
        }
    }
    stages {
        stage('test') {
            steps {
                sh 'pwd'
            }
        }
    }
}
