pipeline {
  agent {
    docker {
      image 'maven:3.3.9-alpine'
    }

  }
  stages {
    stage('a333') {
      parallel {
        stage('a333666') {
          steps {
            sh 'mvn -version'
          }
        }
        stage('666') {
          steps {
            sh '666'
          }
        }
      }
    }
  }
}