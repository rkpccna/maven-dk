pipeline {
  agent any
  stages {
    stage('Code CheckOut') {
      steps {
        git(url: 'https://github.com/rkpccna/maven-dk.git', branch: 'master')
      }
    }
    stage('Build') {
      steps {
        sh 'mvn clean install -f dellcompany/pom.xml'
      }
    }
  }
}