pipeline {
  agent any
  stages {
    stage(‘Lint html’) {
      steps {
        sh ‘tidy -q -e index.html’
      }
    }
  }
}
