pipeline {
  agent {
      label 'production'
    }
    tools {
        maven 'Maven-3.9.9' // Name of the Maven installation in Jenkins
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
