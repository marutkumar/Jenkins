pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                docker build -t marutkumar48/mypythonimage 
            }
        }
        stage('Push'){
             docker push marutkumar48/mypythonimage
        }
    }
}
