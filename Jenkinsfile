pipeline {
    agent any
        stages {
                docker { image 'maven:3-alpine' }
          }
        stage('Back-end') {
            steps {
                sh 'mvn --version'
            }
        }
        
    }
}
