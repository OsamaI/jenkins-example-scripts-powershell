pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        powershell '--version'
      }
    }
    stage('hello') {
      steps {
        powershell 'hello.ps1'
      }
    }
  }
}
