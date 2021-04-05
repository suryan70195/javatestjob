pipeline {
    agent any

    stages {
        stage('---clean---') {
            steps {
                sh "mvn clean deploy"
            }
        }
		stage('---test---') {
            steps {
                sh "mvn test"
            }
        }
		stage('---package---') {
            steps {
                sh "mvn package"
            }
        }
    }
}
