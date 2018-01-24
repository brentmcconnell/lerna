pipeline {
  agent {
    docker {
      image 'nodejs'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}