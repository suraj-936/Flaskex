pipeline {
        agent {
        stage('build') {
                steps {
                    image = docker.build("${IMAGE}")
                }
        }
}
}
