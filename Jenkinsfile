pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
    stage('Example') {
           steps {
                 echo  "Running ${env.BUILD_IO} on ${env.JENKINS_URL}"
                    }
           }
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
