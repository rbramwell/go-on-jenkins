pipeline {
  agent any
  environment {
    GO111MODULES = 'on'
  }
  tools {
    go 'go-1.15.3'
  }
  stages {
    stage('Build') {
      go build
    }
  }
}
