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
        dir(path: 'D:\\Program Files\\Docker Toolbox') {
          bat(script: 'docker images', returnStatus: true, returnStdout: true)
        }

      }
    }
  }
}