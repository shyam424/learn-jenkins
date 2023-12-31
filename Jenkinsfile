pipeline {
   // agent any
agent { node {label 'workstation' } }

environment {
TEST_URL = 'google.com'
}

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('compile') {
            steps {
                echo 'compile'
            }
        }
        stage('Test') {
            steps {
                echo 'test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
                fileExists 'file existed'
            }
        }
    }
}
