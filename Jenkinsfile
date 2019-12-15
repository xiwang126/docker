pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args 'node:6-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
  environment {
    test_env = '1111'
  }
}