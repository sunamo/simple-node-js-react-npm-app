pipeline {
    agent any
    tools {nodejs "nodejs"}

    stages {
        stage('Build') { 
            steps {
                bat 'npm install' 
            }
        }
        // stage('Test') {
        //     steps {
        //         sh './jenkins/scripts/test.sh'
        //     }
        // }
    }
}