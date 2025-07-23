pipeline {
    agent any
     stages {
        stage('Build') {
            steps {
                echo 'Building ...'
            }
        }
        stage('Test') {
            steps {
                echo 'Test stage'
                sh 'test -f build/index.html'
            }
        }
     }
}