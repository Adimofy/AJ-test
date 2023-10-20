pipeline {
  agent any
  tools {
    maven 'maven'
  }
  stages{
    stage('1-cloning project repo'){
      steps{
        checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'jenkins7creds', url: 'https://github.com/Adimofy/AJ-test.git']])
      }
    }
    stage('2-cleans'){
      steps{
        sh 'mvn clean /home/ubuntu/maven-etech/etech-mavenApp/MavenEnterpriseApp-web/pom.xml
'
      }
    }
    stage('3-mavenbuild'){
      steps{
        sh 'mvn package'
      }
    }
  }
}