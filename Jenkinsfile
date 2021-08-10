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
        bat 'echo "hello world good evening"'
      }
    }

    stage('test') {
      steps {
        echo 'hello master good evening'
      }
    }

  }
}
