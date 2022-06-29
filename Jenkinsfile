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
        sh "mkdir somethingelse"
      }
    }
    stage('Deploy') {
      steps {
        sh "cd somethingelse"
        sh "pwd"
      }
    }
  }
}
