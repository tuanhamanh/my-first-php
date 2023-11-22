pipeline {
   agent {
           docker { image 'php:8.2-cli' }
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