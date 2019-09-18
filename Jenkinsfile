pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'test'
      }
    }
    stage('test') {
      parallel {
        stage('chrome_test') {
          steps {
            sh 'xx'
          }
        }
        stage('firefox_test') {
          steps {
            sh 'tes'
          }
        }
        stage('ie_test') {
          steps {
            sh 'test'
          }
        }
      }
    }
    stage('deploy') {
      steps {
        sh 'test'
      }
    }
  }
}