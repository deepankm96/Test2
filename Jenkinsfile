pipeline {
  agent { label 'master' }
	stages {
		stage ('Deploy to production') { 
			steps {
				step { def userInput = input(message:'Do you want to proceed for production deployment?') }
				echo userInput  
		}
		}
  }
  
  }
