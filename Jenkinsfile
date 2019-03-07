pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo $USERID'
      }
    }
  }
  environment {
    ISERID = 'myuser'
  }
}