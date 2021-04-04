pipeline {
  agent any
  stages {
    stage('Pull') {
      steps {
        echo 'Hoang'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sleep 10
          }
        }

        stage('Build 2') {
          steps {
            sleep 20
          }
        }

      }
    }

  }
}