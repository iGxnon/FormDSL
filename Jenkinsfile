pipeline {
  agent any
  stages {
    stage('build') {
      agent {
        docker {
          image 'maven:3-jdk-11'
        }

      }
      steps {
        sh 'echo \'start build formDSL\''
        sh 'mvn package'
      }
    }

  }
}