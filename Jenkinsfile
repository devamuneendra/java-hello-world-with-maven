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

    stage('') {
      steps {
        echo 'hey you triggered pipeline automatically'
      }
    }

  }
}