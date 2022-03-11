pipeline {
   agent none
    stages{
 stage('Test') {
    parallel linux: {
        node('linux') {
            echo "hi"
        }
    }
}
    windows: {
        node('windows') {
            echo "hi hi"
         }
      }
   }
}
