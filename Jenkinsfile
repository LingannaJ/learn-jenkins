pipeline {
    agent {
        lable 'AGENT-1'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'echo this is from build'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo this is from test'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo this is from deploy'
            }
        }
    }
}