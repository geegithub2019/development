pipeline {
  agent any
  stages {
    stage(‘Lint_HTML’) {
      steps {
        sh ‘tidy -q -e index.html’
      }
    }
  }
}
