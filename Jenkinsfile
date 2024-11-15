pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/BrianBrotski/Gradle.git'
            }
        }
        stage('Build') {
            steps {
                sh './gradlew build'
            }
        }
    }
}
