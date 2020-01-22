  
node
{
    stage 'checkout1'

    git url: 'https://github.com/Shrijeeta/sonar_jenkins.git'


     def mvnHome = tool 'M3'

     stage 'Build'


     sh "${mvnHome}/bin/mvn clean test sonar:sonar"
}
