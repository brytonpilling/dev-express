pipeline {
  agent any
  stages {
    stage('First Stage') {
      parallel {
        stage('First Stage') {
          steps {
            echo 'Starting First Step'
          }
        }
        stage('Second Stage') {
          steps {
            echo 'second stage'
          }
        }
      }
    }
    stage('Third Stage') {
      steps {
        echo 'Third'
      }
    }
  }
}