pipeline {
  agent any
  stages {
    stage('FIRST MACHINE') {
      steps {
        powershell 'cd "C:\\Users\\user\\vgdemo";vagrant --version;'
      }
    }

    stage('test') {
      steps {
        powershell 'vagrant --version'
      }
    }

  }
}