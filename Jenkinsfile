/* Requires the Docker Pipeline plugin */
pipeline {
    agent { label "master" }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
