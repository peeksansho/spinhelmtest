#!/usr/bin/env groovy

pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                // 
                echo 'building!'
                sh "git diff -U0  HEAD HEAD~1 nginx/Chart.yaml | grep '^[+-]' | grep -o version || exit 1"
            }
        }
        stage('Test') { 
            steps {
                //
                echo 'testing!'
                sh "sleep 3000"
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
