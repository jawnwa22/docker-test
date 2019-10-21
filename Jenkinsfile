pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'docker build -t jawnwa22/node-web-app .'
      }
    }
    stage('run') {
      steps {
        sh 'docker run -p 3000:3000 -d --rm'
      }
    }
  }
}