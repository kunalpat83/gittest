pipeline {
		 agent none
		 stages {
		 		stage ('Build')
		 		{
		 		 agnet docker{ docker 'maven:3-alpine' }
		 			steps{
		 					echo 'Hello maven'
		 					sh 'maven --version'
		 			}
		 		}
		 		stage ('Test')
		 		{
		 		 agnet docker{ docker 'openjdk:8-jre' }
		 			steps{
		 					echo 'Hello JDK'
		 					sh 'java -version'
		 			}
		 		}

		 }
}
