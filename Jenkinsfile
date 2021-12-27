pipeline {	
	agent any	
	stages {
		stage("Run the code") {
			steps {
				sh """
					python calculator.py
				"""

}
}
stage("Run unit tests"){
    steps {
		sh """
		pytest
		"""
	}
}
}
}
