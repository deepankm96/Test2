pipeline {
  agent { label 'master' }
	
	stages {
		stage ('Deploy to production') { 
			steps {

				script {
					
				def userInput = input(message:'Do you want to proceed for production deployment?')
				
				
				if (userInput == proceed) {
        // do something
        echo "this was successful"
    } if (userInput == abort) {
        // do something else
        echo "this was not successful"
        currentBuild.result = 'FAILURE'
    } 
			}
		}
		}
	}}
