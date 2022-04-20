pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Ben is Building...'
                sh 'uname -a'
            }
        }
        stage('Test') {
            steps {
                echo 'Ben is Testing...'
                sh 'uptime'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Ben is Deploying...'
                sh 'whoami'
            }
        }
    }
}
