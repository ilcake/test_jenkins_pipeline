pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "Hello, World!"'
          }
        }
        stage('') {
          steps {
            sh 'echo "Hello, There! too!"'
          }
        }
        stage('') {
          steps {
            sh 'echo "Hello!!! Hello!!!"'
          }
        }
      }
    }
    stage('Build2') {
      parallel {
        stage('Build2') {
          steps {
            sh 'echo "Build2!"'
          }
        }
        stage('') {
          steps {
            sh 'echo "Build2 !!!"'
          }
        }
      }
    }
    stage('Nap') {
      steps {
        sleep 10
      }
    }
  }
}