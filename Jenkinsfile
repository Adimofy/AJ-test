pipeline {
    agent any
    stages {
        stage('Prosper Stage') {
            steps {
                sh 'echo "Prosper script: OS statistics and Jenkins status check"'
            }
        }
        stage('parallel'){
        parallel{
        stage('erica'){
            steps{
                sh 'echo "Erica script: OS statistics and Jenkins status check"'
            }
        }
        stage('Bill Stage') {
            steps {
                sh 'echo "Prosper script: OS statistics and Jenkins status check"'
            }
        }
        }
        }
        stage('Jonas Stage') {
            steps {
                sh 'echo "Prosper script: OS statistics and Jenkins status check"'
            }
        }
                stage('Gilbet Stage') {
            steps {
                sh 'echo "Prosper script: OS statistics and Jenkins status check"'
            }
        }
    }
}