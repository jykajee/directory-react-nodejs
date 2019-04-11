pipeline {
  agent any
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