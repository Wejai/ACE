pipeline {
  agent any
  stages {
    stage('DEV') {
      steps {
        echo 'hi'
        bat(script: 'buildbar', returnStatus: true, returnStdout: true)
      }
    }
  }
}