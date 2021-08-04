pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'mvn clean install'
      }
    }

    stage('clean') {
      steps {
        echo 'Hello jenkins!'
      }
    }

  }
  triggers {
    pollSCM('* * * * *')
  }
}
