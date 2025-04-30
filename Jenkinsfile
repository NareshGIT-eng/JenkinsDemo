pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi, this is Narasimman K'
			
                }
        }
	    stage('Two'){
		    
		steps {
			input('Do you want to proceed?')
        }
	    }
        stage('Three') {
                when {
                        not {
                                branch "main"
                        }
                }
                steps {
			echo "Hello"
                        }
        }
        stage('Four') {
                                steps {
                                        echo "Running the unit test..."
                                } 
		}
        }
    }
