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
	node1 {
			stage('build') {
				steps {
					echo "building the code"
				}
			}
			stage('get approval') {
				input "deploy to server ?"
			}
		}
	node2 {
			stage('deploy') {
				steps {
					echo "deploying"
				}
				}
}

