pipeline {
    agent any

    stages {
        stage('Example') {
            steps {
                echo  "Running" ${env.BUILD_IO} on ${env.JENKINS_URL}
                    }
           }


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
       }
    }
}
