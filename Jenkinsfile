pipeline {
   agent any
	stages {
      stage('Git Checkout') {
         steps {
            git 'https://github.com/charan0409/parking_backend.git'
		}
	}
	  stage('Build') {
		steps {
			sh 'mvn clean install -Dmaven.test.skip=true'
			}
		}
	}
	}
	
