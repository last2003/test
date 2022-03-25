pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'docker version >>~/test.txt'
                sh 'echo \'OK\''
            }
        }
    }
}
