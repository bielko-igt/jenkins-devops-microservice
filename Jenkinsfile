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


		
	} post {

		always {
			echo 'This runs always'
		}
		success {
			echo 'Success'
		}
		failure {
			echo 'Failure'
		}
	}
}
