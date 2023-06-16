pipeline {
        agent any
        
        stages {
            stage('Stage one') {
                steps {
                    script {
                        sh 'docker ps'
                    }
            
            }
            stage('Stage two') {
                steps {
                    script {
                        sh 'docker images'
                    }
                }
            }
        }
    }
}
