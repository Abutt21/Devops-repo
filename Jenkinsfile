pipeline {
    agent any
    
    stages {
        stage('Check docker process') {
            steps {
                echo 'Checking docker process...'
                sh 'docker ps'
            }
        }
        
        stage('Check docker images') {
            steps {
                echo 'Checking docker images...'
                sh 'docker images'
            }
        }
        
        stage('Check files') {
            steps {
                echo 'Checking files...'
                sh 'ls'
            }
        }
        
        stage('Build docker images') {
            steps {
                echo 'Building docker images...'
                sh 'docker build -t myimage/myapp:2.0 .'
            }
        }
        
        stage('Run Docker container') {
            steps {
                echo 'Running Docker container...'
                sh 'docker run -d --name butt-p myimage/myapp:2.0'
            }
        }
    }
}
