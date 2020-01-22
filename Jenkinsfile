  
pipeline {
    agent any
      stages {
      
      stage('checkout') {
            steps {
                git 'https://github.com/Shrijeeta/sonar_jenkins.git'
            }
        }
        stage('Build') {
            steps {
                sh "mvn clean test sonar:sonar"
            }
        }
               
    }
}
