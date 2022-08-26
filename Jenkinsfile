pipeline {
  agent {
    docker {
      image 'node:lts-alpine '
      args '-p 3000:3000 '
    }

  }
  stages {
    stage('build') {
      agent {
        docker {
          args '-p 3000:3000 '
          image 'node:lts-alpine '
        }

      }
      steps {
        sh 'npm install'
      }
    }

  }
}