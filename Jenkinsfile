pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                docker ps
                docker build .
            }
        }
    }
}
