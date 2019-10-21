pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh '''sh \'node --version\'
sh \'svn --version\''''
      }
    }
  }
}