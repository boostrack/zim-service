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
        stage('') {
          steps {
            sh 'docker ps'
          }
        }
      }
    }
  }
}