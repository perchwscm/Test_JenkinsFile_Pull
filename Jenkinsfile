#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
				sh "ls -ltra"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}