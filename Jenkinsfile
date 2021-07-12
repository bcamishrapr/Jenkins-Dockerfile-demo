pipeline {
    agent { dockerfile true
            label 'slave' 
     }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
