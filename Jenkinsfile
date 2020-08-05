pipline {
    agent any
    environment {
        GO111MODULE=on
    }
    tools {
        go 'go-1.14.6'
    }
    stages {
        stage('Compile') {
            steps {
                sh 'go build'
            }
        }
    }
}