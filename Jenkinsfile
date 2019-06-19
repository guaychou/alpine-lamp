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
    stage('laporkapten') {
      steps {
        sh 'mail -s "Tes email" crossmajor99@gmail.com'
      }
    }
  }
}