pipeline {
    agent {
        label 'Jen_Slave'
    stages {
        stage('Back-end') {
            agent {
                docker { image 'maven:3-alpine' }
            }
            
            steps {
                sh 'mvn --version'
            }
        }
        
    }
}
