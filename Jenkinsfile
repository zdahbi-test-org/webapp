pipeline {
  agent any
  stages {
    stage('Clone repository') {
        /* Cloning the Repository to our Workspace */
        checkout scm
    }
    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }
    stage('Log date') {
      steps {
        sh 'date'
      }
    }
  }
}
