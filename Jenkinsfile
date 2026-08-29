pipeline {
    agent any
    tools {
        maven 'mvn3.9'
        jdk 'jdk17'
    }

    stages {

       stage('mvn compile') {
            steps {
                sh 'mvn compile'
            }
        }
       stage('mvn test') {
            steps {
                sh 'mvn test'
            }
        }
       stage('mvn pkg') {
            steps {
                sh 'mvn package'
            }
        }                
    }
}
