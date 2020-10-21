pipeline {
    agent {
        docker { image 'centos_jenkins:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'ifconfig'
                sh 'hostname'
                sh 'echo ${my_variable}'
                sh 'env'
                sh sleep 60
            }
        }
        stage('Print environment variable') {
            steps {
                sh 'echo "I can access $BUILD_NUMBER in shell command as well."'
            }
        }
    }
}
