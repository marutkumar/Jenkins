pipeline {
    agent {
        docker {
            image 'maven:latest'
        }
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
        
        // Add more stages as needed
    }
}
