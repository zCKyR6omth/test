pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        git(url: 'git@github.com:zCKyR6omth/test.git', branch: 'master')
        sh '''git clone git@github.com:zCKyR6omth/test.git;
mvn clean;'''
      }
    }
  }
}