pipeline {
  agent {
    docker {
      image 'alpine:3.7'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'ls'
        sh 'uname -a'
      }
    }

    stage('error') {
      steps {
        sh 'apk add python3'
      }
    }

  }
}