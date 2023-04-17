pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:lts-slim'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}
