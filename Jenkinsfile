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
        git(url: 'https://github.com/guaychou/alpine-lamp', branch: 'master')
        sh '''git add "aaa.txt"
git commit -m "tes tes"
git push origin '''
      }
    }
  }
}