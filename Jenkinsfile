node { 
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
			}
}
	node {
			stage('build') {
				steps {
					echo "building the code"
				}
			}
			stage('get approval') {
				input "deploy to server ?"
			}
		}
	node {
			stage('deploy') {
				steps {
					echo "deploying"
				}
				}
}

