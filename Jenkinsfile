pipeline {
    agent any

    stages {

        stage('Clone Confirmation') {
            steps {
                echo 'Code pulled successfully from GitHub!'
            }
        }

        stage('List Files') {
            steps {
                bat 'dir'
            }
        }

    }
}
