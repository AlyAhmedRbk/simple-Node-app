pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building App...'
                sh "node --version"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing App...'
                sh "node app.js"
                //sh 'gcloud compute zones list'

            }
        }
    }
}
