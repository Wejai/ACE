pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Welcome to the demo'
      }
    }
    stage('Build') {
      steps {
        bat 'echo "hellowrold"'
        bat 'docker pull ibmcom/ace'
      }
    }
  }
}