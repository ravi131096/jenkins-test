## 6. Parallelization
Try to optimize this Jenkinsfile to reduce the execution time

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Unit Tests') {
            steps {
                echo 'Running unit tests...'
                sh 'mvn test'
            }
        }
        stage('Integration Tests') {
            steps {
                echo 'Running integration tests...'
                sh 'mvn verify'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
