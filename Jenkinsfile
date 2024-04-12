pipeline {
    agent any
    stages {
        stage('auth interface') {
            steps {
                echo 'auth interface'
            }
        }
        stage('build auth interface') { 
            steps {
                sh 'mvn clean install'
            }
        }      
    }
}