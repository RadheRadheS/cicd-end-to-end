pipeline {
    
    agent any 
    
    
    stages {
        
        stage('compile'){
                sh "mvn compile"
        }

        stage('test'){
            sh "mvn test"
        }

        stage('package'){
           sh "mvn clean package"
        }
        
    }
}
