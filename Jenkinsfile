pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      parallel {
        stage('Buzz Buzz') {
          steps {
            echo 'Bees Buzz!'
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

      }
    }

  }
}