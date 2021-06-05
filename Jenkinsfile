pipeline {
  agent any
  stages {
    stage('build01') {
      parallel {
        stage('build01') {
          steps {
            echo 'build01'
          }
        }

        stage('build02') {
          steps {
            echo 'build02'
          }
        }

      }
    }

    stage('test') {
      steps {
        echo 'test'
      }
    }

  }
  environment {
    VERSION = '1.1.1'
  }
}