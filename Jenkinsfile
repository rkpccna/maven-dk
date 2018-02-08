pipeline {
  agent any
  stages {
    stage('Code CheckOut') {
      steps {
        git(url: 'https://github.com/rkpccna/maven-dk.git', branch: 'master')
      }
    }
  }
}