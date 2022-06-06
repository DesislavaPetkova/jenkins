pipeline  {
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
		succsess{
			echo "i run when success"
		}

	}
}
