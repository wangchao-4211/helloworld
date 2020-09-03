pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        lock(resource: '1', inversePrecedence: true, label: '1', quantity: 1, variable: '1')
      }
    }
  }
}