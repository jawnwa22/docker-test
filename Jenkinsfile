pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
  environment {
    label = 'docker-test'
  }
}