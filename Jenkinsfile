pipeline {
    agent any
    tools {
        go 'go-1.11'
        nodejs 'node-12'
    }
    environment {
        GO111MODULE = 'on'
    }
    stages {
        stage('version'){
          steps{
            sh 'echo $JENKINS_HOME'
            sh 'node -v'
            sh 'eval echo "~$USER"'
            sh 'go version'
            sh 'which go'
            sh 'git version'
            sh 'claat version'
            sh 'claat export 1cgOqCw13vT_JXdZpccVhTMJTKoLORd7ZTmNSjbX0fMA'
            sh 'claat export sample.md'   
          }
        }
    }
}

