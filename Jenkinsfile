pipeline {
  agent {
    node {
      label 'v12.13'
    }

  }
  stages {
    stage('build') {
      agent {
        node {
          label 'v12.13'
        }

      }
      steps {
        sh 'yarn install'
      }
    }

  }
}