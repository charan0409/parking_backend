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
			sh '/home/hackathon/softwares/apache-maven-3.6.3/bin/mvn clean install -Dmaven.test.skip=true'
			}
		}
	}
	}
	
