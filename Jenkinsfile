pipeline {
agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/ozmeidan/C--Users-ozm-Documents-GitHub-Calculator-Python.git'
            }
        }
        stage('build') {
            steps {
                bat 'python 1.py'
            }
        
        }
    }
}
