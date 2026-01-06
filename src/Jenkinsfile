
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                credentialsId: 'github-creds',
                url: 'https://github.com/blaxmankumar/ci-cd-pipeline-project.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build started"
            }
        }
    }
}
