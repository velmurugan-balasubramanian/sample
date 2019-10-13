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
            sh 'claat -auth 4/sAGdk5WUNNgTUx28VUC9Vr8SvtrmXEaXnO_sQTfZJo5hjU361v8xdiI export 1rSJlTFkaT_rcSzyfhdzAI1_8ot6V7rKAp9Jj3VVwb6I'
            sh 'claat export hello.md'
          }
        }
    }
}

