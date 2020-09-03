pipeline {
    agent any


    stages {
       stage('Test') {
           steps {
                sh "python3 test.py"
           }
       }
       stage('Build') {
           steps {
                sh "pip3 install ."
           }
       }
}
