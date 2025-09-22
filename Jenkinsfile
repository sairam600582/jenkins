pipeline {
  agent any
  stages {
    stage('checkout Git') {
      steps {
        git 'https://github.com/sairam600582/jenkins.git'
      }
    }

    stage('buidding') {
      steps {
        echo 'building '
      }
    }

    stage('testing') {
      steps {
        echo 'testing'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}