pipeline {
	    agent any
	    stages {
	        stage('Checkout project') {
	            steps {
	                script {
	                    git branch: "master",
	                       credentialsId: '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',
	                       url: 'https://github.com/kanis07/jenkins_lab9.git'
	                }
	            }
	        }
}