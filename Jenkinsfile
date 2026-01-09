pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/asmisalha07/finaldevops.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t asmisalha07/myapp:v1 .'
            }
        }
    }
}
