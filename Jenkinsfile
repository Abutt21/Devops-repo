pipeline {
    agent any
         
        stage('Docker Build') {
            steps {
                // Build the Docker image
                // Make sure Docker is installed on the Jenkins agent
                sh 'docker build -t myimage/myapp:2.0 .'
            }
        }
        
      }
}
