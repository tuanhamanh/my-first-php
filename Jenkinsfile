pipeline {
    agent {
        node {
            docker { image 'php:8.0.20RC1-fpm-alpine3.16' }
            }
      }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                    php --version
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "doing test stuff.."
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}