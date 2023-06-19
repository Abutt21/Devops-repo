pipeline {
    agent any
    stages {
        stage('Check docker process') {
            steps {
                sh 'docker ps'
            }
        }
        stage('Check docker images') {
            steps {
                sh 'docker images'
            }
        }
        stage('Check files ') {
            steps {
                sh 'ls'
            }
        }
        stage('build docker image') {
            steps{
        sh 'docker build -t myimage/myapp:2.0 ' {
                     
            }
        }  
