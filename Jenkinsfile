
pipeline {
    agent any

    stages {
        stage('Build') {
             steps{
              withMaven(maven : 'maven'){
              sh 'mvn compile'
              }
              }
            }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

    }
}