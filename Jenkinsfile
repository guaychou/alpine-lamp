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
        sh '''pwd
touch aaa.txt'''
        git(branch: 'master', url: 'https://github.com/guaychou/alpine-lamp')
      }
    }
    stage('laporkapten') {
      steps {
        sh '''git add aaa.txt
git config --global user.email "crossmajor99@gmail.com"
git config --global user.name "kevinchou"
git commit -m "add aaa.txt"
git push origin master'''
      }
    }
  }
}