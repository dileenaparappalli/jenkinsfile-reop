pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "stage-1"
            }
        }
        stage('Test') { 
            steps {
                sh 'python3 test.py'            }
        }
        stage('Deploy') { 
            steps {
                echoo "stage-3"
            }
        }
    }
}
