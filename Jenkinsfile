pipeline {
    agent {
        docker { image 'node:14-alpine_notexist' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
