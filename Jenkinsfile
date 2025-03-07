pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'git@github.com:ganesh-dhumal/devops-learning.git'
            }
        }

        stage('Run a Script') {
            steps {
                sh 'echo "🚀 Jenkins Pipeline is Running!"'
            }
        }
    }
}
