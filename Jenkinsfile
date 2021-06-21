pipeline {
  agent {
    docker {
      image 'harbor.jiayuntong.com/cloudplant/dotnet:v1.0'
    }

  }
  stages {
    stage('dotnet') {
      agent {
        docker {
          image 'harbor.jiayuntong.com/cloudplant/dotnet:v1.0'
        }

      }
      steps {
        sh 'dotnet --version'
      }
    }
  }
}