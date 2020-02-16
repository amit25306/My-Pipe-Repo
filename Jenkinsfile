pipeline {
	agent any 
		stages {
			stage('clone') {
				steps {
					echo "Cloning from git"
				}
			}
			stage('test') {
				steps {
					echo "executing test cases"
				}
			}
			stage('build') {
				steps {
					echo "building the code"
				}
			}
			stage('get approval') {
				input "deploy to server"
			}
		}	
}

