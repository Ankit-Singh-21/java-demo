pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
            git branch: 'main',
            url: 'https://github.com/Ankit-Singh-21/java-demo.git'
          }
        }

        stage('Compile') {
            steps {
                bat 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Hello'
            }
        }
    }
}