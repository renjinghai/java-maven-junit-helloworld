pipeline {
    agent any 
    tools { 
        maven 'Maven 3.5.0' 
    }
    stages {
        stage('Compile') {
            steps {
               echo 'compile'
                sh 'mvn compile'
            }
        }
        stage('Test') {
            steps {
                echo 'test'
                sh 'mvn test'
            }
        }
        stage('Verify') {
            steps {
                echo 'verify'
                sh 'mvn verify'
            }
        }
    }
}
