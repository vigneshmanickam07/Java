pipeline {
    agent any
    stages {
        stage('Back-end') {
            steps {
                    docker { image 'maven:3-alpine' }
                {
                     sh 'mvn --version'
            }
        }
      }
    }
}
