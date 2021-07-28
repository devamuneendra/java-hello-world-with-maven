pipeline {
    agent any

    tools {
        maven "maven-3.6.3"
    }

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/devamuneendra/java-hello-world-with-maven.git'
            }
        }
        stage('Build') {
            steps {
                bat "mvn clean install"
            }
        }
    }
}
