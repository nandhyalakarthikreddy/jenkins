pipeline {
    agent {
        node {
            label 'Agent-1'
        }
    }
    stages {
        stage('Build') { 
            steps {
                echo "Building" 
            }
        }
        stage('Test') { 
            steps {
                echo "Testing"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploying"
            }
        }
    }
    post{
        always{
            echo 'i will always say hello again and again'
        }
    }   
}