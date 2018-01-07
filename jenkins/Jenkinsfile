
pipeline {
    agent any

    stages {
        stage('Compile') {
             steps{
              withMaven(maven : 'maven'){
               bat'mvn clean package'
              }
              }
            }
    }
}