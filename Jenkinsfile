pipeline{
    agent { label 'docker' { image 'docker'} }
    stages{
        stage('Build'){
            steps{
                 sh 'docker build -t marutkumar48/mypythonimage .'
            }
        }
        stage('Push'){
            steps{
                sh 'docker push marutkumar48/mypythonimage'
            }
        }
    }
}
