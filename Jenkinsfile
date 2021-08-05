pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'mvn clean install'
      }
    }

    stage('Print') {
      steps {
        bat 'helloworld'
      }
    }

  }
}