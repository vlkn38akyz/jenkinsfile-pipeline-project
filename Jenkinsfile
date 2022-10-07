pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
        stage('build') {
            steps {
                echo 'Volkan_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
        stage('build2') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run2') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }
    }
}