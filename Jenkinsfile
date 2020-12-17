pipeline {
  agent {
    docker {
      image 'python'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo \'Hola Mundo\''
      }
    }

    stage('Probar') {
      steps {
        sh 'python3 -m unittest discover -v'
      }
    }

  }
}