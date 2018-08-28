pipeline {
  agent any
  stages {
    stage('use job1') {
      steps {
        build(job: 'test1', quietPeriod: 1)
      }
    }
  }
  environment {
    ENV = 'beta'
  }
}