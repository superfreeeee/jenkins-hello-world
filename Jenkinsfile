pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                java --version
                mvn --version
                docker --version
            }
        }
    }
}
