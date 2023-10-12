pipeline {
    agent any
    stages {
        stage('Prosper Stage') {
            steps {
                sh '/var/lib/jenkins/workspace/Bachanou'
            }
        }
        stage('parallel'){
        parallel{
        stage('erica'){
            steps{
                sh '/var/lib/jenkins/workspace/Bachanou'
            }
        }
        stage('Bill Stage') {
            steps {
                sh '/var/lib/jenkins/workspace/Bachanou'
            }
        }
        }
        }
        stage('Jonas Stage') {
            steps {
                sh '/var/lib/jenkins/workspace/Bachanou'
            }
        }
                stage('Gilbet Stage') {
            steps {
                sh '/var/lib/jenkins/workspace/Bachanou'
            }
        }
    }
}