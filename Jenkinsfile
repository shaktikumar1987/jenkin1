pipeline {
    agent any    

stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
    stages {
        stage('checking with powershell') {
            steps {
                powershell '''write-host "this is running form jenkins  pipeline 2"

		get-service'''
            }
        }
    }
}
