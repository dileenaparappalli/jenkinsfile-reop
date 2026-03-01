pipeline {
    //agent any
    agent {label 'agent - 2'}
    stages {
        stage('Build') { 
            steps {
                echo "stage-1"
                echo "Huraay....."
            }
        }
        stage('Test') { 
            steps {
                sh 'python3 test.py'   
                echo "Executed python script"
                echo "Moving to next stage"
            }
        }
        stage('Deploy') { 
            steps {
                echo "stage-3"
            }
        }
    }
}
