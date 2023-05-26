/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.2-eclipse-temurin-11-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
