pipeline {
    agent any

    stages {
        stage ('Build') {
            steps {
                withMaven(maven: 'Maven_3_5_2') {
                    sh 'mvn -B -DskipTests clean package'
                }
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
