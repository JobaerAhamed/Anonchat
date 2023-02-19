pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'npm run build'
      }
    }
  tools {
      go 'node-18'
    }
  }
}
