pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        git(url: 'https://github.com/mk201309/test.git', branch: 'master', credentialsId: 'a336a145992d5f5d97ab3fabea58fa7e51b33840')
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