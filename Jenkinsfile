pipeline {
  agent any
  stages {
    stage('Buikd') {
      steps {
        sh 'env ; which maven ;mvn clean install'
      }
    }
  }
}