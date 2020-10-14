pipeline {
  agent any
  stages {
    stage('Build') {
      tools {
        gradle 'gradle6.7'
      }
      steps {
        sh 'gradle clean build'
      }
    }

  }
}