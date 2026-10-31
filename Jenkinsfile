pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
                echo 'Hello World'
            }
        }
    }

    post {
        success {
            echo 'Build and tests successful!'
        }
    }
}
