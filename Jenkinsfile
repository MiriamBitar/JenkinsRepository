/* Requires the Docker Pipeline plugin */
pipeline {
    agent { label "built-in" }
    stages {
        stage('build') {
            steps {
                sh 'docker --version'
                sh 'docker ps'
            }
        }
    }
}
