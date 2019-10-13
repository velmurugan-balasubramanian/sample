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
            sh 'claat export sample.md -auth 4/qQHR5YnYsCNphGK2FsDw3egv5UglI_ssIL86EtfYzFBP9W0Dm6eOsK'
          }
        }
    }
}

