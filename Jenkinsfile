pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                checkout scm
            }
        }
        stage('Check Permissions') {
            steps {
                sh 'ls -l ./list_files.sh'
            }
        }
        stage('Grant Permissions') {
            steps {
                sh 'chmod +x ./list_files.sh'
            }
        }
        stage('Execute Bash Script') {
            steps {
                sh './list_files.sh'
            }
        }
    }
}
