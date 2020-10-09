pipeline {
  agent any
  stages {
    stage('1st stage') {
      parallel {
        stage('1st stage') {
          steps {
            sh 'echo $asd'
          }
        }

        stage('2nd') {
          steps {
            git(poll: true, url: 'dfh', branch: 'sgdg', credentialsId: 'dg')
          }
        }

      }
    }

  }
  environment {
    asd = 'adsasd'
  }
}