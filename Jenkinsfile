pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      parallel {
        stage('Buzz Build') {
          steps {
            bat(script: 'docker ps', returnStatus: true)
          }
        }

        stage('Buzz Branch') {
          steps {
            echo 'This a branch that i need to test'
          }
        }

        stage('testtt') {
          steps {
            echo 'is it possible'
          }
        }

      }
    }

    stage('Bees Bees') {
      parallel {
        stage('Bees Bees') {
          steps {
            echo 'Bees Buzz'
            echo 'Bees Buzzing Again'
          }
        }

        stage('Testing the branch') {
          steps {
            echo 'I am done'
          }
        }

        stage('Testing Docker Instance') {
          steps {
            bat(script: ' docker ps', label: 'Running a docker instance in interactive mode', returnStdout: true)
          }
        }

      }
    }

  }
  environment {
    BUZZ_NAME = 'wORKER bEE'
  }
}