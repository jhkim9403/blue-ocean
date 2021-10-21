pipeline {
  agent any
  stages {
    stage('bulid') {
      steps {
        sh 'sh test.sh'
      }
    }

  }
  environment {
    http = 'test1'
  }
}