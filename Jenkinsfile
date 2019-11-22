pipeline {
    agent any

    tools {
            maven 'Maven-3.6.2'
            jdk 'Java-1.8'
    }
    stages {

        stage ('compile-demo') {

            steps {
               sh 'mvn clean compile'
            }

        }
        stage ('test') {

              steps {
                sh 'mvn test'
              }

         }

        stage ('install') {

              steps {
                sh 'mvn test'
              }

         }

    }
}
