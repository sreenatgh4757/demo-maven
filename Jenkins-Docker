pipeline {
    agent {
        docker {
            image 'node:10.0.0' 
            args '-p 3000:3000 -u root ' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
