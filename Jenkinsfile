pipeline {
  agent any
  stages {
    stage('Start') {
      parallel {
        stage('Start1') {
          steps {
            echo 'Hello!'
          }
        }
        stage('Start2') {
          steps {
            echo 'World!'
          }
        }
      }
    }
    stage('Build') {
      parallel {
        stage('Build1') {
          steps {
            echo 'Building!'
          }
        }
        stage('Build2') {
          steps {
            echo '!!'
          }
        }
        stage('Build3') {
          steps {
            echo '????'
          }
        }
      }
    }
    stage('Final') {
      steps {
        echo 'Finished!'
      }
    }
  }
}