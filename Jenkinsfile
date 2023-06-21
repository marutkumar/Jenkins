pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh ' docker build -t marutkumar48/mypythonimage .'
            }
        }
        stage('Push'){
            sh 'docker push marutkumar48/mypythonimage'
        }
    }
}
