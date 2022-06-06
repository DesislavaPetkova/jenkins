pipeline  {
	//agent any
	agent { docker { image 'maven:3.6.3'} }
	stages {
		stage('Build') {
			steps {
				//sh 'mvn --version' 
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integartion Test') { 
			steps {
				echo "Integartion Tests"
			}
		}
	}
	post{
		always{
			echo "I run always."
		}
		success{
			echo "i run when success"
		}

	}
}
