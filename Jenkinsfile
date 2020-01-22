  
node
{
    stage 'checkout1'

    git url: 'https://github.com/mangesh2310/excersise1.git'


     def mvnHome = tool 'M3'

     stage 'Build'


     sh "${mvnHome}/bin/mvn clean test sonar:sonar"
}
