pipeline {
  agent any
  stages {
    stage('Bring up the first machine') {
      steps {
        bat 'C:\\Users\\user\\windowsbatch\\vgdemo1.bat'
      }
    }

    stage('Bring up the second machine') {
      steps {
        bat 'C:\\Users\\user\\windowsbatch\\vgdemo2.bat'
      }
    }

    stage('Bringup the third machine') {
      steps {
        bat 'C:\\Users\\user\\windowsbatch\\vgdemo3.bat'
      }
    }

  }
}