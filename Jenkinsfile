pipeline {
    agent any
    stages {
        stage('Prosper Stage') {
            steps {
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
        stage('parallel'){
        parallel{
        stage('erica'){
            steps{
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
        stage('Bill Stage') {
            steps {
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
        }
        }
        stage('Jonas Stage') {
            steps {
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
                stage('Gilbet Stage') {
            steps {
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
    }
}