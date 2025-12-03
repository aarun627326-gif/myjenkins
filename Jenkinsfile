pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main', url: 'https://github.com/aarun627326-gif/myjenkins.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the Project..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the Project..."
            }
        }
    }
}
