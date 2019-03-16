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
        bat(script: '"C:\\Program Files\\Git\\bin\\bash.exe" --login -i "d:\\Program Files\\Docker Toolbox\\start.sh"', returnStatus: true)
      }
    }
  }
}