pipeline {
    agent {docker { image 'node:14-alpine' } }

    environment {
        NAME = 'Jake'
    }

    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                echo "${NAME}"
            }
        }
    }
}