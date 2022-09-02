pipeline {
  agent any
  stages {
    stage('build') {
      agent {
        docker {
          image 'maven:3-jdk-11'
          args '-v maven-repo:/root/.m2'
        }

      }
      steps {
        sh 'echo \'start build formDSL\''
        sh 'mvn package'
      }
    }

  }
}