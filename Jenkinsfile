/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pwd'
            }
        stage('prepare test env') {
            steps {
                sh 'docker compose up'
            }
        }
    }
}
