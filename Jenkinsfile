/* Requires the Docker Pipeline plugin */
pipeline {
    agent { label "built-in" }
    triggers {
        pollSCM('')
    }
    stages {
        stage('build') {
            steps {
                sh 'docker --version'
            }
        }
    }
}
