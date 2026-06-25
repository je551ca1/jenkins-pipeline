pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Starting Build Stage'

                sh '''
                    pwd
                    ls -la
                    touch build.txt
                    ls -la
                '''
            }
        }

        stage('Test') {
            steps {
                echo 'Starting Test Stage'

                sh '''
                    pwd
                    ls -la
                '''
            }
        }

        stage('Deploy') {
            steps {
                echo 'Starting Deploy Stage'

                sh '''
                    mkdir -p deploy
                    mv build.txt deploy/
                    ls -la deploy/
                '''
            }
        }

    }
}
