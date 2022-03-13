pipeline {
    agent { 
        dockerfile true 
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                echo 'Hello world'
            }
        }
    }
}
