pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Example: sh 'npm install' or sh './gradlew build'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example: sh 'npm test' or sh './gradlew test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Example: sh 'scp build/* user@server:/var/www/html/'
            }
        }
    }
}
