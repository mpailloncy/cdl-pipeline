#!/usr/bin/env groovy

pipeline {
	
	agent any

	stages {
		stage("build") {
			steps {
				echo "Building my super project"
				script {
				    for(int i=0; i < 9; i++) {
				        sleep 10
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

