pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        sh 'npm install'
      }
    }
    stage('tests skipped') {
      steps {
        sh 'node test'
      }
    }
    stage('node server') {
      steps {
        sh 'node server'
      }
    }
  }
}