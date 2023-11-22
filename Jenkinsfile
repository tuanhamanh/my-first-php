pipeline {
    agent {
        node {
            label 'docker-agent-php-8.1'
            }
      }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                    cd my-app
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