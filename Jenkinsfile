pipeline {
    agent {
        node {
            label ''
        }
    }
    stages {
        stage('test') {
            steps {
                sh 'cd /var/cmp/infrastructure && ./env.sh build int'
                sh 'cd /var/cmp/infrastructure && ./env.sh start int'
            }
        }
    }
}
