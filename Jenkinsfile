pipeline {
  agent {
    docker {
      image 'node:6-alphine'
      args '-p 3000:300'
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