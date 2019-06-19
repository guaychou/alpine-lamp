pipeline {
  agent any
  stages {
    stage('create') {
      steps {
        sh 'echo "Createee aaaa"'
      }
    }
    stage('error') {
      steps {
        sh 'mkdir kontrolfile'
        git(branch: 'master', url: 'https://github.com/guaychou/alpine-lamp')
      }
    }
  }
}