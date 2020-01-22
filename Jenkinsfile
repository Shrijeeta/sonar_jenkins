  
pipeline {
    agent any
      stages {
      
      stage('checkout') {
            steps {
                git 'https://github.com/Shrijeeta/sonar_jenkins.git'
              
              
            }
        def mvnHome = tool 'M3'
        }
        
        stage('Build') {
            steps {
                sh "${mvnHome}/bin/mvn clean test sonar:sonar"
            }
        }
               
    }
}
