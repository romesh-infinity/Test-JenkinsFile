pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'ip a'
            }
        }
        stage('test') {
            steps {
                sh 'ec2metadata'
            }
        }
    }
}
