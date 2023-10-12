pipeline {
    agent any
    stages {
        stage('compile a build binary'){
         parallel{
          stage('sub-job1'){
           steps{
            sh 'echo "Erica script: OS statistics and Jenkins status check"'
            }
        }
    }
}
        stage('Prosper Stage') {
            steps {
                sh 'echo "Prosper script: OS statistics and Jenkins status check"'
            }
        }
        stage('testing'){
         parallel{
          stage('sub-job2'){
           steps{
            sh 'echo "Erica script: OS statistics and Jenkins status check"'
            }
        }
    }
}
        stage('Jonas Stage') {
            steps {
                sh 'echo "Prosper script: OS statistics and Jenkins status check"'
            }
        }
    }
}