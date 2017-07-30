pipeline {
    agent any 
    tools { 
        maven 'Maven 3.5.0' 
    }
    stages {
        stage('Compile') {
            steps {
               echo 'compiling'
                sh 'mvn compile'
            }
        }
        stage('Test') {
            steps {
                echo 'testing'
                sh 'mvn test'
            }
        }
        stage('Verify') {
            steps {
                echo 'verifing'
                sh 'mvn verify'
            }
        }
    }
}
