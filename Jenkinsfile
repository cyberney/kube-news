pipeline {
    agent any

    stages {

        stage ('Build Docker Image') {
            steps {
                script {
                    dockerapp = docker.build("sidneyrodrix/kube-news:${env.BUILD_ID}", '-f ./src/Docker' ./src)
                }
            }
        }
    }