pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/SRCEM-AIML/C4_49_vaishnavililhare_Assignment2.git'
            }
        }
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t vaishnavililhare/studentproject .'
            }
        }
        stage('Push to Docker Hub') {
            steps {
                sh 'docker push vaishnavililhare/studentproject'
            }
        }
    }
}
