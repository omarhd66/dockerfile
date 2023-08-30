pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'docker build -t buildalpine-githubjenkins . '
                sh 'docker tag buildalpine-githubjenkins:latest docker.io/20216627/buildalpine:githubjenkins'
            }
           
    }
        stage('push dockerhub') {
            steps {
                sh 'docker push docker.io/20216627/buildalpine:githubjenkins'
            }
           
    }
    }
}


