pipeline {
    agent any
    stages {
        stage('Prosper Stage') {
            steps {
                sh './ajtest.sh'
            }
        }
        stage('parallel'){
        parallel{
        stage('erica'){
            steps{
                sh './ajtest.sh'
            }
        }
        stage('Bill Stage') {
            steps {
                sh './ajtest.sh'
            }
        }
        }
        }
        stage('Jonas Stage') {
            steps {
                sh './ajtest.sh'
            }
        }
                stage('Gilbet Stage') {
            steps {
                sh './ajtest.sh'
            }
        }
    }
}