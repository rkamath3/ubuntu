pipeline {
agent {
    dockerfile true
}
stages {
    stage('Build image') {
        steps {
            script{
                docker.build aggregator-dev
            }
        }
    }
}
}
