pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stages ('List all files') {
        stage {
            steps {
                ls -a
            }
        }
    }
}
