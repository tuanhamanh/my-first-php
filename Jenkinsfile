pipeline {
   agent {
           docker { image 'php:8.0.20RC1-fpm-alpine3.16' }
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
    }
}