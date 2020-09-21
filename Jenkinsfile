pipeline {
    agent {
        docker { image 'centos:latest' }
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
