pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac myclass.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java myclass"""
				}
			}
			
		}
	}
