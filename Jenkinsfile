pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo \'start build formDSL\''
        withGradle()
      }
    }

  }
}