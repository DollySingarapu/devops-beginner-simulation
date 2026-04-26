pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'python3 app.py'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker build -t team-app .'
            }
        }
    }
}
