/* Requires the Docker Pipeline plugin */
pipeline {
    agent { label "Built-In Node" }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
