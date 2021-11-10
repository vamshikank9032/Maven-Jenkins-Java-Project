pipeline {
    agent { label 'jenkinsslave' }
    
  tools {
     maven "maven3.6"
  }
  
    stages {
        stage('Prepare-Workspace') { 
            steps {
                git credentialsId: 'github-server-credentials', url: 'https://github.com/vamshikank9032/Maven-Jenkins-Java-Project.git'
            }
        }
    }
}
