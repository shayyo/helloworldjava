pipeline {
    agent {
        docker { image 'centos_jenkins:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'yum install -y net-tools'
                sh 'ifconfig'
            }
        }
    }
}
