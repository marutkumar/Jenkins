pipeline {
  agent{
        docker {
            image 'maven:latest'
        }
    }
  stages {
    stage('Build Docker Image') {
      steps('Hello World') {
        echo "Hello World"
          }
        }
    stage('apt update'){
        steps{
          sh 'apt update'
        }
    }
      }
    }
