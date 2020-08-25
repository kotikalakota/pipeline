pipeline {
	agent any
	stages {
		stage ('Compile'){
			steps {
				echo "Compile - Successful";
			}
		}
		stage ('JUnit'){
			steps {
				echo "JUnit - Successful";
			}
		}
		stage ('Quality'){
			steps {
				echo "Quality - Successful";
			}
		}
		stage ('Deploy'){
			steps {
				echo "Deploy - Successful";
			}
		}
		
	}
	post {
		always {
			echo 'This will always run'
		}
		success {
			echo 'will run on success'
		}
		failure {
			echo 'failures happened'
		}
		unstable {
			echo 'unstable happene'
		}
		changed {
			echo 'change happened'
		}	
	}
}
