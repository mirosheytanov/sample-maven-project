pipeline {
  agent any
  
  stages {
  stage('maven install') {
      steps {
        withMaven(maven: 'mvn') {
          sh 'mvn clean install'
        }
      }
    }
  }
}
