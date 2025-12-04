pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/afnantypical/node-app.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "No tests available"'
            }
        }

        stage('Run App') {
            steps {
                sh 'npm start &'
                echo "Node app started on port 3000"
            }
        }

    }
}
