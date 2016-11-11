#!/usr/bin/env groovy

pipeline {
	
	agent any

	stages {
		stage("build") {
			steps {
				echo "Building my super project"
				sh "ls -rtl"
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
