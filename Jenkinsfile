pipeline {
  agent any

  stages {
    stage('Build Docker Image') {
      steps {
        script {
          docker.withRegistry('https://registry.hub.docker.com', 'dockerhub-credentials') {
            def image = docker.build('marutkumar48/python:tag', '.')
            image.push()
          }
        }
      }
    }
  }
}
