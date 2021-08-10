pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac jenkinsdemo.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java jenkinsdemo"""
				}
			}
		 stage ("finish") {
			steps {
				echo "Finished Successfully"
		
				}
		 }
		 
			
		}
	}
