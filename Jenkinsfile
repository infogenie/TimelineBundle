pipeline {
  agent {
    docker {
      image 'nginx'
    }
    
  }
  stages {
    stage('stage') {
      steps {
        sh 'echo "ls -lah"'
      }
    }
  }
  environment {
    aa = 'cc'
  }
}