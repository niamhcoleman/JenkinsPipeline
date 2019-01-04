pipeline {
    agent any

    stages {
        stage ('Build') {
            steps {
                sh 'javac Student.java'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
