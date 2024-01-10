pipeline {
  agent any
    stages{
      stage('clean'){
        steps{
         sh 'mvn clean'
        }
      }
      stage('compile'){
        steps{
         sh 'mvn complie'
        }
      }
       stage('install'){
        steps{
         sh 'mvn install'
        }
      }
    }
  }

