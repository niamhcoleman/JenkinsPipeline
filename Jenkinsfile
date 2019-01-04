pipeline {
    agent any

    stages {
        stage ('Build') {
            steps {
                withMaven(maven: 'Maven_3_5_2') {
                    sh 'mvn clean compile'
                }
            }
        }

        stage ('Test') {
            steps {
                withMaven(maven: 'Maven_3_5_2') {
                    sh 'mvn test'
                }
            }
        }
    }
}
