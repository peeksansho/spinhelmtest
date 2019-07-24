#!/usr/bin/env groovy

pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                // 
                echo 'building!'
                sh "sleep 3000"
            }
        }
        stage('Test') { 
            steps {
                //
                echo 'testing!'
                sh "sleep 1"
            }
        }
        stage('Deploy') { 
            steps {
                //
                echo 'deploying!'
                sh "sleep 1"
            }
        }
    }
}
