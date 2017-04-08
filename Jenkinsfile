pipeline {
  agent any
  stages {
    stage('run1') {
      steps {
        bat(script: 'echo "testare"', returnStatus: true, returnStdout: true)
      }
    }
  }
}