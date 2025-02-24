pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/ranadesh/Javapipeline.git'
            }
        }

        stage('Build with Maven') {
            steps {
                sh '/mnt/c/Users/HP/Downloads/apache-maven-3.9.9'
            }
        }
    }
}

