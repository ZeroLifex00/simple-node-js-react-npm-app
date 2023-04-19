pipeline {
  agent {
    docker {
      args '-p 3000:3000 --dns 10.32.53.254'
      image 'node:lts-bullseye-slim'
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
