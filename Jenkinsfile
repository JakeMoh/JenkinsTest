pipeline {
    agent {docker { image 'node:14-alpine' } }

    environment {
        NAME = 'Jake'
    }

    stages {
        stage('build') {
            steps {
                echo 'Building'
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