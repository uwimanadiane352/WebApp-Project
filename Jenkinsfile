pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                echo 'Installing Node.js dependencies...'
                bat 'npm install'
            }
        }

        stage('Run Tests') {
            steps {
                echo 'Running Tests...'
                bat 'npm test'
            }
        }
    }
}
