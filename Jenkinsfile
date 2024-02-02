pipeline {
    agent {
        node {
            label 'docker-agent-python'
        }
    }

    triggers {
        pollSCM '*/5 * * * *'
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
