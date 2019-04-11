pipeline {
  agent {
    docker {
      image 'node:8-alpine'
      args '-p 5000:5000'
    }

  }
  stages {
    stage('init') {
      steps {
        sh 'npm install'
      }
    }
    stage('tests ') {
      steps {
        sh 'npm test'
      }
    }
    stage('node server') {
      steps {
        sh 'node server'
      }
    }
  }
}