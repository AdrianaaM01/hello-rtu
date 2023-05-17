pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Check node version') {
            steps {
                sh "node --version"
            }
        }
    }
}