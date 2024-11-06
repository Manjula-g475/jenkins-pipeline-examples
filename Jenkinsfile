#!groovy

pipeline {

  agent any
  stages {
    stage('Checkout-SCM') {
      steps {
        checkout scmGit(branches: [[name: '*/main' ]], extensions: [],
      }
    }
  }
}
