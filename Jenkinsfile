pipeline {
  agent any
  stages {
    stage('build') {
      agent {
        node {
          label 'v12.13.0'
        }

      }
      steps {
        build 'build'
      }
    }

  }
}