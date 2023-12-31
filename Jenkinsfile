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
               sh 'ansible -i 172.31.16.126, all -e ansible_user=${SSH_USER} -e ansible_password =${SSH_PSW} -m ping'
            }
        }

    }
}
