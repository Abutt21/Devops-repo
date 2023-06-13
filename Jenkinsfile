pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac BubbleSort.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java BubbleSort'
            }
        }
    }
}
