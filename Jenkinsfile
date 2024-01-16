pipeline {
    agent any
    stages {
        stage('SCM Checkout') {
            steps {
                script {
                    git 'https://github.com/prio21/BankingApplication.git'
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
