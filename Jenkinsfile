pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/SRI-RAKSHA48/ADDA-Lab4'
            }
        }

        stage('Build and Test') {
            steps {
                bat 'mvn clean test'
            }
        }
    }
}