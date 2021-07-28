pipeline {
	agent any
	triggers {
    cron ('*/2 * * * *')
	}
	stages {
		stage ('Build') {	
			steps {
				echo 'Build stage'
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