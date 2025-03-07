pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/ganesh-dhumal/devops-learning.git'
            }
        }

        stage('Run a Script') {
            steps {
                sh 'echo "🚀 Jenkins Pipeline is Running with a Public Repo!"'
            }
        }
    }
}
