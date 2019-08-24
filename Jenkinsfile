pipeline {
  agent { label 'master' }
	
	stages {
		stage ('Deploy to production') { 
			steps {

				script {
					
				def userInput = input(message:'Do you want to proceed for production deployment?')
				echo "$userInput"
				
				if (userInput == true) {
        // do something
        echo "this was successful"
    } else if (userInput == false) {
        // do something else
        echo "this was not successful"
        currentBuild.result = 'FAILURE'
    } 
			}
		}
		}
	}}
