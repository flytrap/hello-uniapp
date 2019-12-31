pipeline {
  agent {
    docker {
      args '-p 3333:3000'
      image 'node:12.14.0'
    }

  }
  stages {
    stage('build') {
      agent {
        docker {
          image 'node:v12.13.0'
        }

      }
      steps {
        sh 'yarn install'
      }
    }

  }
}