pipeline {
    agent any
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'gradle:6.7-jdk11'
                    
                    reuseNode true
                }
            }
            steps {
                sh 'ls'
                sh 'touch file'
        }
        }
        stage('Front-end') {
            agent {
                docker { image 'node:16.13.1-alpine' }
                     reuseNode true
        
              }
            steps {
                    sh 'ls'
               }
        }
    }
}

