
pipeline {
    agent { docker { image 'maven:3.8.6-openjdk-11-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
/*
node {
    stage('Build') {
        docker.image('maven:3.8.6-openjdk-11-slim').inside {
            sh 'mvn --version'
        }
    }
}*/
