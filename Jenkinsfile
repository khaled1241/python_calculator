pipeline {	
	agent any	
	stages {
		stage("Run the code") {
			steps {
				sh """
					python3 calculator.py
				"""
}
}
stage("Run unit tests") {
    steps {
		sh """
		python3 -m pytest
		"""
	}
}
}
}
