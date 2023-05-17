pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stages ('Check node version') {
        stage {
            steps {
                bat "node --version"
            }
        }
    }
}
}
