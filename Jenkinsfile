pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                docker: {
                    image 'docker'
                }
            }
            steps {
                sh 'python --version'
                
                sh 'python app.py' 
            }
        }
    }
}
