pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
                sh 'python pipeline.py'
            }
        }
        stage('java-build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('java-run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }        
    }
}