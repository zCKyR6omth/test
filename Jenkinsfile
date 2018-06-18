pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        git(credentialsId: 'testcreds', url: 'git@github.com:zCKyR6omth/test.git', branch: 'master')
      }
    }
  }
}