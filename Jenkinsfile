pipeline {
    agent any
    stages {
        stage('SCM Checkout') {
            steps {
                script {
                    git 'https://github.com/saukumar42/Banking-App-Rest-API'
                }
            }
        }
        stage('Compile-Package') {
            steps {
                script {
                    bat 'mvn package'
                }
            }
        }
        
    }
}
