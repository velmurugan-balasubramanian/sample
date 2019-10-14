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
            sh 'go version'
            sh 'which go'
            sh 'git version'
            sh 'go get github.com/googlecodelabs/tools/claat'
            sh 'claat version'
     
          }
        }
    }
}

