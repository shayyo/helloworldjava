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
                echo 'Deploying....'
            }
        }
        stage('Run BASH script') {
            steps {
                sh "#!/bin/bash \n" +
                    "cd /tmp \n" +
                    "echo $PWD \n" +
                    "./ssh.sh"
            }
        }
    }
}
