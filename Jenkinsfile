#!/usr/bin/env groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build in progress'
                script {
                    git branch: 'master',
                            credentialsId: 'Git_Credential_Id',
                            url: 'git@github.com:ramzibk/jenkinsLab.git'
                }
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