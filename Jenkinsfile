pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'gcc example.c'
                sh 'chmod +x a.out'
                sh './a.out'
            }
        }
    }
}
