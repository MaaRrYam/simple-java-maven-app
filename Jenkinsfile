pipeline {
  agent {
    docker {
      args '-p  3000:3000'
      image '18-alpine3.15'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}