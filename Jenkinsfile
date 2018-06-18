pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''git clone git@github.com:zCKyR6omth/test.git;
mvn clean;'''
        git(url: 'git@github.com:zCKyR6omth/test.git', branch: 'master')
      }
    }
  }
}