pipeline {
  agent none
  stages {
    stage('stage') {
      steps {
        sleep 2
      }
    }
    stage('') {
      steps {
        waitForQualityGate()
      }
    }
  }
}