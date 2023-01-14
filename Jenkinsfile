pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                //echo 'Testing..'
                bat "mvn clean compile test"
            }
        }
        stage('Build') {
            steps {
                //echo 'Building..'
                bat "mvn clean install"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}