pipeline {
    agent{ 	
       label "java-docker-slave"
    }
	stages {
        stage('Checkout From GitHub Repository') {
            steps {
                checkout scm
            }
          }
		}
	}
