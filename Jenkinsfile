pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/ruwaisaafsal/CAR-WEBSITE.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
