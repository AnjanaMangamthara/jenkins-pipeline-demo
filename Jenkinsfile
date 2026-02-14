pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Repo cloned automatically by Jenkins'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage running'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage running'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully 🎉'
        }
    }
}
