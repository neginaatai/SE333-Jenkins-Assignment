pipeline {
    agent any
    tools {
        maven 'M3'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'sleep 1000'
                sh 'echo Build Complete'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'echo Tests Passed'
            }
        }
    }
}
