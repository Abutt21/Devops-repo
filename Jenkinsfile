pipeline {
    agent any
         
        stage('Docker Build') {
            steps {
                // Build the Docker image
                
                sh 'docker build -t myimage/myapp:2.0 .'
            }
        }
        
      }
}
