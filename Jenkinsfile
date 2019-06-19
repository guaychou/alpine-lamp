pipeline {
  agent any
  stages {
    stage('PWD') {
      steps {
        sh 'pwd'
      }
    }
    stage('Docker build image') {
      steps {
        sh 'cd nginxalpine/ && docker build -t  nginx-alpine . '
      }
    }
  }
}