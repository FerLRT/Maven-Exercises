pipeline {
  agent any
  stages {
    stage('Hello world') {
      steps {
        echo 'HELLO!'
      }
    }

    stage('Compile') {
      steps {
        sh 'mvn clean install'
      }
    }

    stage('ended') {
      steps {
        echo 'He terminado'
      }
    }

  }
}