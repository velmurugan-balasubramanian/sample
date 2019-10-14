pipeline {
    agent any
    tools {
        go 'go-1.11'
    }
    environment {
        GO111MODULE = 'on'
    }
    stages {
        stage('version'){
          steps{
            sh ' go version'
            sh 'which go'
            sh 'git version'
            sh 'claat export hello.md'
          }
        }
    }
}

