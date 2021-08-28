pipeline {
    agent any
    tools {
        maven 'Maven'
        //added a comment //
    }
    stages {
        stage('buildstage') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}

