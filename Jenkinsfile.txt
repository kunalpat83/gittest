pipeline {
	agent any
		stages {
			stage('One') {
				steps {
					echo 'Hi, This is Stage 1'
				      }
			}
			stage('Two') {
				steps {
					echo 'Hi, This is Stage 2'
				      }
			}
	}
}
