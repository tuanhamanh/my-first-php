pipeline {
   agent {
           docker { image 'node:20.9.0-alpine3.18' }
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