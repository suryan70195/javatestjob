pipeline {
    agent any

    stages {
        stage('---compile---') {
            steps {
                sh "mvn compile"
            }
        }
		stage('---test---') {
            steps {
                sh "mvn test"
            }
        }
	    
	     stage('---install---') {
            steps {
                sh "mvn install"
            }
        }
		stage('---deploy---') {
            steps {
                sh "mvn deploy"
            }
        }
    }
}
