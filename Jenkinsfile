pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'df -h' 
            }
        }
        stage('Test') { 
            steps {
                echo 'hi'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'bi'
            }
        }
    }
}
