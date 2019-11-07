pipeline {
  agent any
  stages {
    stage('hello world') {
      steps {
        sh 'sh \'echo hello\''
      }
    }
    stage('test') {
      steps {
        sh 'sh \'echo test\''
      }
    }
  }
  environment {
    hello = 'word'
  }
}