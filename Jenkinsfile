pipeline {
    agent any
    stages {
        stage('Pipeline Stages'){
            steps {
                sh "ls"
            }
        }
        stage('second stage'){
            steps {
                sh "pwd"
            }
        }
        stage('Third Stage'){
            steps {
                sh "echo 'Hello World'"
            }
        }
        stage('Fourth Stage'){
            steps {
                sh "touch newfile.txt"
            }
        }
        stage('Fifth Stage'){
            steps {
                sh "mv newfile.txt movedfile.txt"
            }
        }
    }
}
