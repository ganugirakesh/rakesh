/* node('slave'){
sh 'cd /opt;ls'
sh 'cd /opt/;sudo mkdir chef'  
} */
pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}

