pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/ricpiva/java-rest-api-calculator-master.git'
                sh './mvnw clean compile'
                }
        }
    }
}