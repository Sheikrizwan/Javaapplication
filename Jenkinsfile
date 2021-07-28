pipeline {
	agent any
	triggers {
    pollSCM ('*/2 * * * *')
	}
	stages {
		stage ('Build') {	
			steps {
				echo 'Build stage'
				sh 'mvn clean install'
				}
			}
		stage ('Test') {
			steps {
				echo 'Test stage'
				}
			}
		stage ('Deploy') {
			steps {
				echo 'Deploy stage'
				}
		    }
		}
	}	
