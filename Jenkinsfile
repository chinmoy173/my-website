pipeline {
  agent any
  stages {
    stage('Buzz Branch') {
      steps {
        echo 'This is the first test to bring  a machine up'
        powershell 'cd C:\\Users\\user\\vgdemo; vagrant suspend;'
      }
    }

  }
}