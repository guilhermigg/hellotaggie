pipeline {
    agent any
    stages {
        stage('DockerImage') {
            steps {
                sh 'docker build -t helloTaggie .'
            }
        }
    }
}
