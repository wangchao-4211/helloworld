pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            lock(resource: '1', inversePrecedence: true, label: '1', quantity: 1, variable: '1')
          }
        }
        stage('sssss') {
          agent any
          environment {
            JAVA_HOME = '/usr/local/jdk1.8.0_221'
          }
          steps {
            archiveArtifacts(artifacts: '111', excludes: '111')
          }
        }
      }
    }
    stage('shell') {
      steps {
        sh '''pwd
pwd'''
      }
    }
  }
}