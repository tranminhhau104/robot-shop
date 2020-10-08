pipeline {
  agent any
  stages {
    stage('1st stage') {
      steps {
        withAnt(installation: 'as', jdk: 'ads')
        sh 'echo $asd'
      }
    }

  }
  environment {
    asd = 'adsasd'
  }
}