pipeline {
    agent any
    stages {
        stage('Build') { 
             steps {
                sh 'mvn clean package'
        }
        }
        stage('SonarQube analysis') { 
             steps {
                withSonarQubeEnv('sonar_vitec') { 
                sh 'mvn sonar:sonar'
                }
        }
        }
        }
        
    }
