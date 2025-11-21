pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps { git 'https://github.com/your_repo' }
        }
        stage('Build') {
            steps { sh 'mvn clean package' }
        }
        stage('Test') {
            steps { sh 'mvn test' }
        }
        stage('Deploy') {
            steps { echo 'Deploy completed successfully' }
        }
    }
}
