pipeline {
    agent any

    tools {
        maven "M3"
    }
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'java --version'
                sh 'mvn --version'
                sh 'docker --version'
            }
        }
    }
}
