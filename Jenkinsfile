pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo \'test\''
      }
    }
    stage('t2') {
      steps {
        echo 't2'
        sh 'echo \'t2 2\''
      }
    }
  }
}