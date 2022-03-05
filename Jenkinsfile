pipeline {
    agent any
    stages {
        stage('Example stage 1') {
            environment {
                BITBUCKET_COMMON_CREDS = credentials('shushan')
            }
            steps {
                echo($BITBUCKET_COMMON_CREDS)
            }
        }
    }
}
