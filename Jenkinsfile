pipeline {
    agent any

    stages {

        stage('Test Stage') {
            steps {
                echo 'Jenkins Pipeline is Working!'
            }
        }

        stage('System Info') {
            steps {
                sh 'uname -a'
            }
        }

        stage('Docker Check') {
            steps {
                sh 'docker --version'
            }
        }
    }
}
