pipeline {
    //agent any
    agent { node { label 'workstation' } }

    environment {
    TEST_URL = "google.com"
    }
    stages {
        stage('Hello') {
            steps {
                //echo 'Hello World'
                echo TEST_URL
            }
        }


    }
}
