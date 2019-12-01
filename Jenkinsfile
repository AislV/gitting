pipeline {
agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/AislV/gitting.git'
            }
        }
        stage('build') {
            steps {
                bat 'new.py'
            }
        }
    }
}
