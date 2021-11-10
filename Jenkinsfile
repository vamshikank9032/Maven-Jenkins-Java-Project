pipeline {
    agent { label 'buildserver' }
    
  tools {
     maven "maven3.0"
  }
  
    stages {
        stage('Prepare-Workspace') { 
            steps {
                git credentialsId: 'github-server-credentials', url: 'https://github.com/vamshikank9032/Maven-Jenkins-Java-Project.git'
            }
        }
    }
}
