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
            }
        }
    }
}
