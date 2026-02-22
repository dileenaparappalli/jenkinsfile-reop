pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "stage-1"
                echo "Huraay....."
            }
        }
        stage('Test') { 
            steps {
                sh 'python3 test.py'            }
        }
        stage('Deploy') { 
            steps {
                echo "stage-3"
            }
        }
    }
}
