pipeline {
    agent any
    stages {
        stage('Build') { 
             steps {
                sh 'mvn clean package'
        }
        }
         stage('push to jfrog') { 
             steps {
                rtUpload (
                serverId: 'vitecarti',
                spec: '''{
                    "files": [
                {
                "pattern": "target/*.war",
                "target": "Vignesh/"
                }
         ]
    }''',
                )
                }
        }
        }
        
    }
