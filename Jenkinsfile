pipeline {
  agent { label 'master' }
	stages {
		stage ('Deploy to production') { 
			steps {
				script {
					
				def userInput = input(message:'Do you want to proceed for production deployment?')
				echo userInput  
			}
			}
		}
		}
}
