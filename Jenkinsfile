pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac Jenkinsfile.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Jenkinsfile'
            }
        }
    }
}
