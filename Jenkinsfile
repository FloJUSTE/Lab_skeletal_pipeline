pipeline {
  agent any
  stages {
    stage('Flutty Build') {
      agent any
      steps {
        sh 'echo Edited Placeholder'
      }
    }

    stage('Flutty Test') {
      steps {
        sh 'sleep 5'
        sh 'echo Success!'
      }
    }

    stage('Flutty Deploy') {
      steps {
        echo 'Deploy!!!!'
      }
    }

  }
}