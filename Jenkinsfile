
pipeline {
    agent any

    stages {
        stage('Compile') {
             steps{
              withMaven(maven : 'maven'){
               sh 'mvn clean package'
              }
              }
            }
    }
}