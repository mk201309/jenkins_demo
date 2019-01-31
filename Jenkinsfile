pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        git(url: 'git@github.com:mk201309/test.git', branch: 'master')
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
    stage('Deploy2') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}