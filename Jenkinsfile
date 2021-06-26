pipeline {
    agent {
        docker { image 'ngnix-image' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
