node {

   stage('Preparation') { //for display purposes
      git 'https://github.com/padmaanumani/OnlineBanking'
      // Get the Maven tool.
      // ** NOTE: This 'M3' Maven tool must be configured
      // **       in the global configuration.           
   }
   stage('Build') {
      // Run the maven build<appndid>

         sh "mvn clean package sonar:sonar -DskipTests=True"
         
     
   }
   stage('Results') {
         sh "mvn clean"
   }
}
