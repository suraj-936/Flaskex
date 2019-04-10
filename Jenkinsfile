pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                dockerfile true
                }
            }
            steps {
                sh 'python --version'
               
            }
        }
}
