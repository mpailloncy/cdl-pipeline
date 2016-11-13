#!/usr/bin/env groovy

pipeline {
	
	agent any

	stages {
		stage("build") {
			steps {
				script {
					echo "Building my super project"
				    for(int i=0; i < 9; i++) {
				        sleep 5 
				        echo "Building step ${i}"
				    }
				}
			}
		}

		stage("test") {
			steps {
				echo "Testing super code"
			}
		}

		stage("deploy") {
			steps {
				echo "Deploying my super app"
			}
		}
	}

}

