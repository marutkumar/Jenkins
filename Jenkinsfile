pipeline {
    agent {
        docker {
            // Specify the Docker image to use
            image 'maven:latest'
            // You can also add other Docker agent options here if needed
        }
    }

    stages {
        stage('Build') {
            steps {
                // Your build steps here
                sh 'mvn clean install'
            }
        }
        
        // Add more stages as needed
    }
}
