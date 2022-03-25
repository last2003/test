pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'git version >>~/test.txt'
                sh 'echo \'OK\''
            }
        }
    }
}
