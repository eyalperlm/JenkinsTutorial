pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Building the application'
            }
        }
        
        stage('test') {
            steps {
                echo 'Testing the application'
            }    
        }    
    }
    
    post {
        success {
            echo 'pipeline success!'
        }
        failure {
            echo 'pipeline failure!'
        }  
    }    
}
