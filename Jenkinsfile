pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                dockerfile {
                    image 'python:2.7' 
                }
            }
            steps {
                sh 'python --version'
                
                sh 'python app.py' 
            }
        }
    }
}
