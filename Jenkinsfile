/* Requires the Docker Pipeline plugin */
pipeline {
    agent { label "node" }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
