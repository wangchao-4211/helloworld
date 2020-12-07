pipeline {
  agent {
    docker {
      image 'maven:3.3.9-alpine'
    }

  }
  stages {
    stage('Stage 1') {
      agent any
      steps {
        echo 'Hello world!'
        sh 'mvn -version'
      }
    }
  }
}