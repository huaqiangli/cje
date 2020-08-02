pipeline {
  agent any
  stages {
    stage('download_code') {
      steps {
        echo 'download code stage'
      }
    }

    stage('build') {
      steps {
        echo 'build the code stage'
      }
    }

    stage('test ') {
      steps {
        echo 'test on linux server'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy to stage environment'
      }
    }

  }
}