pipeline {
    agent any
    stages {
        stage('Clone Git Repository') {
            steps {
                // GitHub access
                git branch: 'main', url: 'https://github.com/vishnuv1230/week-4.git'
            }
        }
        stage('Run Java Program') {
            steps {
                // Run a Java program
                bat 'javac code.java'
                bat 'java code'
            }
        }
        stage('Run Python Program') {
            steps {
                // Run a Python script
                bat 'python3 code.py'
            }
        }
    }
}
