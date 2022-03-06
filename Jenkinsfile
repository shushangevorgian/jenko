pipeline {
    agent any
    parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
        string(name: 'Alfa', defaultValue: 'Hello', description: 'How should I greet the world?')
    }
    stages {
        stage('Example') {
            steps {
                sh 'exit 1'
            }
        
    }
}
post {
        failure {
            echo  "This is a fail"
        }
    }
}
