pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'mvn test'
      }
    }

    stage('test') {
      steps {
        sh 'mvn test'
      }
    }

  }
}