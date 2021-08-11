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
        bat 'echo "hello world good morning test"'
      }
    }

    stage('test') {
      steps {
        echo 'hello test branch'
      }
    }

  }
    triggers {
    pollSCM('* * * * *')
  }
}
