pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('code') {
            steps {
                echo 'Hello World'
            }
        }
        stage('security') {
            steps {
                echo 'Hello World'
                error 'its wrong'
            }
        }
    }
}
