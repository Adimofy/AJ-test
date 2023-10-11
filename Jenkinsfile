pipeline {
    agent any
    stages {
        stage('parallel-job'){
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
        stage('parallel-job'){
         parallel{
          stage('sub-job2'){
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
    }
}