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
        sh "mkdir else"
      }
    }
    stage('Deploy') {
      steps {
        sh "cd else"
        sh "touch example.txt"
        sh "ls"
      }
    }
  }
}
