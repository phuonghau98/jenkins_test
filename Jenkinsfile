pipeline {
	agent {
		docker {
			image 'node:14-stretch'
		}
	}
	stages {
		stage('Build') {
			steps {
				sh 'npm install'
			}
		}
	}
}
