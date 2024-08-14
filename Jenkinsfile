pipeline {
    agent any

    stages {
        stage('MASTER branch') {
            steps {
                sh 'echo "this is MASTER branch"'
            }
        }

        stage('Sprint1 Application') {
            steps {
                sh 'echo "sprint1 application"'
            }
        }

        stage('deploy app') {
            steps {
                sh 'echo "deploying application"'
            }
        }
    }
}

