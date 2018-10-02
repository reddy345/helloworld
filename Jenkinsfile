pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'test', quietPeriod: 1, wait: true)
      }
    }
  }
}