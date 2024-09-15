pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello from the build stage'
      }
    }

    stage('test') {
      steps {
        echo 'hello from test stage'
      }
    }

    stage('deploy') {
      steps {
        echo 'hello from the deploying stage'
        input(message: 'do you want to deploy?', ok: 'yes,i do')
      }
    }

    stage('finish') {
      steps {
        echo 'congratulation'
      }
    }

  }
}