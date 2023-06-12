/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.0-eclipse-temurin-11' label 'vm1'} }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'hostname'
            }
        }
    }
}