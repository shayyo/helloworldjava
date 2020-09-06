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
                    "echo \"current dir is: $PWD\" \n" +
                    "cd /tmp \n" +
                    "echo \"current dir is: $PWD\" \n" +
                    "./ssh.sh"
            }
        }
    }
}
