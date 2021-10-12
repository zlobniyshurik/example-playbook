pipeline {
    agent any
    stages{
        stage('Some stage'){
            steps {
                sh 'echo 1'
                sh 'echo 2'
                sh 'echo 3'
            }
        }
        stage('Run'){
            steps {
                sh 'echo 1'
                sh 'echo 2'
            }
        }
        stage('Build'){
            steps {
                sh 'echo 1'
                sh 'echo 2'
            }
        }
        stage('Deploy'){
            steps {
                sh 'echo 1'
                sh 'echo 2'
            }
        }
    }
}