pipeline {
    agent any 

    stage {
        stage('Build Assets') {
            agent any 
            steps {
                echo 'Building Assets'
            }
        }
        stage('Test') {
            agent any
            steps {
                echo 'Testing stuff...'
            }
        }
    }
}
