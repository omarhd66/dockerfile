pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
       stage ('List folder'){
          sh """
             ls -al
             ls -l
          """
    }
       
    }
}
