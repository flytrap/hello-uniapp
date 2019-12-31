pipeline {
  agent {
    docker {
      image 'node:v12.13.0'
      args '-p 3333:3000'
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