pipeline {
    agent {
        node {
            label 'docker-agent-python'
        }
    }

    stages {
        stage('Building') {
            steps {
                echo 'Building...'
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploying') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
