pipeline {
  agent {
    node {
      label 'production'
    }

  }
  stages {
    stage('Builddd') {
      steps {
        sh 'mvn clean'
      }
    }

    stage('Testtt') {
      steps {
        sh 'mvn test'
      }
    }

    stage('Deployyy') {
      steps {
        sh 'mvn package'
      }
    }

  }
}