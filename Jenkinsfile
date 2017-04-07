pipeline {
  agent any
  stages {
    stage('') {
      steps {
        fileExists 'test.gpj'
      }
    }
    stage('test') {
      steps {
        sleep 10
      }
    }
    stage('finish') {
      steps {
        sh 'uptime'
      }
    }
  }
}