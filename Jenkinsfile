pipeline {
    agent { 
        dockerfile {
        filename 'Dockerfile'   
        label 'slave1'
        args '-v /tmp:/tmp'
    } 
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
