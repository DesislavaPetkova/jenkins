pipeline  {
	agent any
	stages{
		stage('Build') {
			echo "Build"
		}
		stage('Test') {
			echo "Test"
		}
		stage('Integartion Test') { 
			echo "Integartion Tests"
		}
	}
	post{
		always{
			echo "I run always."
		}
		succsess{
			echo "i run when success"
		}

	}
}
