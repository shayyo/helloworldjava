pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, keepAll: false, reportDir: 'myrepo', reportFiles: 'index.html', reportName: 'HTML Report', reportTitles: ''])
                echo 'Deploying....'
            }
        }
    }
}
