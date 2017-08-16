pipeline {
    agent {
        node {
            label ''
        }
    }
    stages {
        stage('test') {
            steps {
                sh 'cd /var/cmp/infrastructure && pwd'
                sh 'cd /var/cmp/infrastructure && env.sh start int'
            }
        }
    }
}
