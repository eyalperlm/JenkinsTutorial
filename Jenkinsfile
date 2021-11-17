pipeline {
    agent { docker { image 'maven:3.3.3' } }
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
}
