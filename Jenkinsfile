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
            bat'npm install'
                echo 'Building..'
            }
        }
        stage('SAST Scan') {
            steps {
             //   bat 'sonar-scanner' 
           //  withSonarQubeEnv('laptop') {
                        // some block
             //           bat 'sonar-scanner' 
              //      }             
                echo 'Scanning..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
        //        bat 'npm start &'
            }
        }
    }
}