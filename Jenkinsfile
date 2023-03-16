/* Requires the Docker Pipeline plugin */
pipeline {
    agent { label "built-in" }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
