pipeline {
    agent any
        stages {
        stage {
         docker { image 'maven:3-alpine' }
          }
        stage('Back-end') {
            steps {
                sh 'mvn --version'
            }
        }
        
    }
}
