pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
            checkout scm
            sh 'apt install nodejs'
            sh'npm install'
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
    }
}