pipeline {
    agent any

    stages {
        stage('Build') {
        bat '''
        javac -cp "C:\\Users\\Emma\\junit4\\junit-4.13-beta-1.jar";"C:\\Users\\Emma\\hamcrestcore\\hamcrest-all-1.3.jar";. "Student.java" "StudentTest.java"
        '''
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
