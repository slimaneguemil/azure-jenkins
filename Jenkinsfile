@Library('github.com/slimaneguemil/demo-shared-pipeline') _

pipeline {
  agent any
  stages {
    stage('Call Library Hello-World Function') {
      steps {
        script {
          helloWorld()
        }
      }
    }
  }
}