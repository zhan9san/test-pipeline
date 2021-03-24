pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'feature a'
                echo 'Building..'
                sh 'pwd'
                sh 'ls'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
