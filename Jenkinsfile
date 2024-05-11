#!/usr/bin/env groovy
pipeline {
    agent any

    stages {
        stepe('Checkout in progress') {
            steps {
                script {
                    git branch: 'master',
                        credentialsId: 'Git_Credential_Id',
                        url: 'git@github.com:ramzibk/jenkinsLab.git'
                }
            }
        }
        
        stage('Build') {
            steps {
                echo 'Build in progress'
            }
        }

        stage('Test') {
            steps {
                echo 'Test in progress'
            }
        }

        stage('Deploy') {
            steps {
                echo 'deploy in progress'
            }
        }
    }
}