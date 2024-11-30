
pipeline {
    agent any
    stages{
        stage('Git access'){
            steps{
                git branch : 'main' ,url :'https://github.com/navachaithanya77/week-4.git'
            }
        }

        stage('Java execution'){
            steps{
                bat 'javac code.java'
                bat 'java code'
            }
        }
        stage('Python execution'){
            steps{
                bat 'python code.py'
            }
        }
    }
}
