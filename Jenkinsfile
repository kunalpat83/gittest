pipeline {
	agent any
	parameters {
		string(name: 'KUNAL',default: '',description: 'THIS IS MY NAME')
		text(name: 'JENKINS',default: 'TEST',description: 'LEARNING JENKINS')
		choice(name: 'CHOICE',choices['one','two','three'],description: 'Choose any one')
		password(name: 'Password',default: 'secret',description: 'enter the password')
		file(name: 'filename', description: 'Enter the name of the file to upload')
	}

	stages {
			stage('Build') {
							steps {
									echo "Hello ${params.KUNAL}"
									echo "Select any ${params.CHOICE}"
							}
						}
	}
}
