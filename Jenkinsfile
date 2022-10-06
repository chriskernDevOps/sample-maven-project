pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
        withMaven(maven: 'maven3') {
    sh 'mvn clean install'
        sh 'mvn clean install'
       }
      }
    }

  }
}
