pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'ls -lah'
          }
        }
        stage('error') {
          steps {
            sh 'ls -lah '
          }
        }
      }
    }
  }
}