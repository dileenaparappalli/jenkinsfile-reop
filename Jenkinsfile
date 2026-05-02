pipeline {
    agent any
    //agent {label 'worker-agent'}
    stages {
        stage('Build') { 
            steps {
                echo "stage-1"
                echo "Huraay....."
                echo "Build stage completed"
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
                echo "success"
                echo "Completed"
            }
        }
    }
}
