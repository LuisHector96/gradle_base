pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'echo hello #./gradlew clean test --no-daemon'
            }
        }
        stage('Build') {
            steps {
                sh './gradlew build'
            }
        }
    }
}
