pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'mvn clean install'
      }
    }

    stage('extract') {
      steps {
        zip(zipFile: 'file', archive: true, dir: 'C:\\Drifters')
      }
    }

  }
}