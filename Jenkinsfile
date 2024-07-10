pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        powershell 'pwsh --version'
      }
    }
    stage('hello') {
      steps {
        powershell 'pwsh hello.ps1'
      }
    }
  }
}
