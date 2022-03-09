pipeline {
  agent any
  stages {
    stage('docker') {
      parallel {
        stage('docker') {
          steps {
            sh 'echo "hello mr sachin"'
          }
        }

        stage('stage 2') {
          steps {
            sh 'step 2 parallel'
            echo 'go on'
          }
        }

      }
    }

  }
}