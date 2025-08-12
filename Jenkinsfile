pipeline {
    agent {
        label 'docker-enabled-agent'
    }
    stages {
        stage('Build') {
            steps {
                sh 'docker run --rm node:16-alpine node -v'
            }
        }
    }
}
