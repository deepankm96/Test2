pipeline {
  agent { label 'master' }
	
	stages {
		stage ('Deploy to production') { 
			steps {
				when {
 			   // case insensitive regular expression for truthy values
    			expression { return token ==~ /(?i)(Y|YES|T|TRUE|ON|RUN)/ }
				}
			steps {
    /* step */
				echo 'yes'
				}
				//script {
					
				//def userInput = input(message:'Do you want to proceed for production deployment?')
				//echo userInput  
			//}
			}
		}
		}
}
