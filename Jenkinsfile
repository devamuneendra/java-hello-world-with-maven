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
        echo 'Hello jenkins! good evening ((()))))********eyu48r09rio'
      }
    }

  }
  triggers {
    pollSCM('* * * * *')
  }
}
