pipeline {
  agent {
    docker {
      image 'composer'
      args 'composer'
    }

  }
  stages {
    stage('isntall') {
      steps {
        cleanWs(cleanWhenFailure: true, cleanWhenAborted: true)
      }
    }
  }
}