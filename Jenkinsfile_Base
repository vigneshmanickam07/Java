
pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo TESTED'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo DEPLOYED'
            }
        }
    }
}
