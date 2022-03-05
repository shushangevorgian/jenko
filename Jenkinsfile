pipeline {
    agent {
        // Define agent details here
    }
    stages {
        stage('Example stage 1') {
            environment {
                BITBUCKET_COMMON_CREDS = credentials('shushan')
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
