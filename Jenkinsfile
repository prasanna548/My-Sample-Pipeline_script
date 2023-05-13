pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                cleanWs()
                echo 'Hello World 1'
                checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/prasanna548/sample2.git']])
            }
        }
        stage('test') {
            steps {
                echo 'Hello World 2'
            }
        }
        stage('3') {
            steps {
                echo 'Hello World 3'
            }
        }
        
    }
    
}
