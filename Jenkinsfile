pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'build step'
          }
        }
        stage('build 2') {
          steps {
            echo 'build 2'
          }
        }
      }
    }
    stage('unit tests') {
      agent any
      steps {
        echo 'test step executing'
      }
    }
  }
}