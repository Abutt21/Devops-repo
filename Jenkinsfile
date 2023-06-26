pipeline {
    agent any
    
    stages {
        stage('Check docker process') {
            steps {
                sh 'docker ps'
            }
        }
        
        stage('Check docker images') {
            steps {
                sh 'docker images'
            }
        }
        
        stage('Check files') {
            steps {
                sh 'ls'
            }
        }
        
        stage('Build docker images') {
            steps {
                sh 'docker build -t myimage/myapp:2.0 .'
            }
        }
        
        stage('Run Docker container') {
            steps {
                sh 'docker run -d --name contra myimage/myapp:2.0'
                sh 'docker logs mycontainer'
            }
        }
    }
}
