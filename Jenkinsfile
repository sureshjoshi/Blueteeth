pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh \'./gradlew compileDebugSources\''
      }
    }
  }
}