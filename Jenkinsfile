pipeline {
    agent { docker { image 'node:14-alpine' } }
    stages {
        stage('build') {
            stage('Build') {
                steps {
                    sh 'npm install'
                }
            }
            stage('Test') { 
                steps {
                    sh 'npm test' 
                }
            }
        }
    }
}
