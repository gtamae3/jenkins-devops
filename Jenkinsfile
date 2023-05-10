pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	}
	post {
		always {
			echo 'T run always.'
		}
		success {
			echo 'I run when success'
		}
		failure {
			echo 'I run when failed'
		}
	}
}
