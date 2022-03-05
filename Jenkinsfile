pipeline {
    agent {
        // Define agent details here
    }
    stages {
        stage('Example stage 1') {
            environment {
                BITBUCKET_COMMON_CREDS = credentials('9413ae6e-87a1-4d4d-8b43-4843adaf29d5')
            }
            steps {
                // 
            }
        }
        stage('Example stage 2') {
            steps {
                echo($BITBUCKET_COMMON_CREDS)
                // 
            }
        }
    }
}
