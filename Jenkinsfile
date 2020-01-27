#!/usr/bin/env groovy

// Obtaining an Docker server instance defined in Jenkins:

pipeline (
	agent {
		docker { image 'ubuntu:latest' }
	}
	stages (
		stage (Test){
			steps {
				echo "Hello world"
			}
		}
	
	)
)