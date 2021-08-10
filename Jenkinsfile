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
        ws(dir: 'C:\\Users\\edevpul\\Desktop\\linuxcommands')
      }
    }

  }
}