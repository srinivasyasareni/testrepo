pipeline {
  agent {
    docker {
      image 'maven'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''echo this is build stage
mvn --version
hostname -i
id'''
      }
    }
  }
}