pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/prath1234/Currency-Converter.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building application..."
            }
        }

        stage('Docker Build') {
            steps {
                echo "Building Docker file"
            }
        }

        stage('Run Container') {
            steps {
                echo "Running docker container"
            }
        }
    }
}
