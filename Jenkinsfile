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
        stage('Check files ') {
            steps {
                sh 'ls'
            }
        }
         sh 'docker build -t myimage/myapp:2.0 ' {
                            
            }
        }
        
    }
}




