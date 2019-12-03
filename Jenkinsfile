pipeline {
  agent any
  stages {
    stage(‘Built’) {
      steps {
        sh ‘tidy -q -e /home/ubuntu/test.html’
      }
    }
  }
}
