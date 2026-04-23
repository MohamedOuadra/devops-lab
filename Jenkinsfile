pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/MohamedOuadra/devops-lab.git', credentialsId: 'github-creds'
            }
        }
        stage('Test') {
            steps {
                bat 'echo Jenkinsfile is working!'
            }
        }
    }
}
