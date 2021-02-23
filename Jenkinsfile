pipeline {
    agent {docker { image 'node:14-alpine' } }

    environment {
        NAME = 'Jake'
    }

    stages {
        stage('build') {
            steps {
                sh 'Building'
                echo "${NAME}"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}