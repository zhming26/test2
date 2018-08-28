pipeline {
  agent any
  stages {
    stage('use job1') {
      steps {
        cleanWs(deleteDirs: true)
      }
    }
  }
  environment {
    ENV = 'beta'
  }
}