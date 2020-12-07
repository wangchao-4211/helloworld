pipeline {
  agent {
    docker {
      image 'maven:3.3.9-alpine'
    }

  }
  stages {
    stage('a') {
      steps {
        sh 'mvn -version'
      }
    }
  }
}