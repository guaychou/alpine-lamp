pipeline {
  agent any
  stages {
    stage('PWD') {
      steps {
        sh 'pwd'
      }
    }
    stage('email me ') {
      steps {
        mail(subject: 'Lapor email', body: 'Coba pelaporan', from: 'kevinchou', replyTo: 'kevinchou', to: 'crossmajor99@gmail.com')
      }
    }
  }
}