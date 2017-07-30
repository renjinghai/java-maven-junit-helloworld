pipeline {
    agent any 
    tools { 
        maven 'Maven 3.5.0' 
    }
    stages {
        stage('Compile') {
            steps {
               echo 'dev'
                sh 'mvn compile'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Verify') {
            steps {
                sh 'mvn verify'
            }
        }
    }
}
