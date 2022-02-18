pipeline {
    
    agent {
    node {
        label 'laptop'
     }
    }
    stages {
        stage('Build') {
            steps {
            checkout scm
            sh 'sudo apt install nodejs'
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