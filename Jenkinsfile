pipeline {
    agent any
    stages {
        stage('verify') {
            steps {
                bat 'mvn -v'
            }
        }
        stage('compile') {
            steps {
                bat 'mvn clean compile'
            }
        }
    }
}
