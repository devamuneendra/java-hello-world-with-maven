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
        bat 'echo "hello world"'
      }
    }

    stage('test') {
      steps {
        input(message: 'Do you want to Test?', id: 'Test')
      }
    }

  }
}