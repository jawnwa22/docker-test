pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
      label 'docker-test'
      additionalBuildArgs '-t docker-test'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}