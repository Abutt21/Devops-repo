pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac Jenkinsfile'
            }
        }
        stage('Run') {
            steps {
                sh 'Jenkinsfile'
            }
        }
    }
}
