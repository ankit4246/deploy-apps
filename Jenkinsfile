pipeline {
    agent any

    stages {
        
        stage('Building') {
            steps {
                echo 'The Code will be now be built into an artifact'
            }
        }
        
        stage('Testing') {
            steps {
                    "npm test"
            }
        }
        stage('Staging') {
            steps {
                    "npm install"
            }
        }
        
        stage('Deploy') {
            steps {
                "npm start"
            }
        }
    }    
}