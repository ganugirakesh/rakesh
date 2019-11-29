/* node('slave'){
sh 'cd /opt;ls'
sh 'cd /opt/;sudo mkdir chef'  
} */
pipeline {
    agent {
        docker { image 'nginx' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}

