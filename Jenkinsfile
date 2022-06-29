pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh "sudo apt update"
      }
    }
    stage('Test') {
      steps {
        sh "mkdir example"
      }
    }
    stage('Deploy') {
      steps {
        sh "cd example"
        sh "pwd"
      }
    }
  }
}
