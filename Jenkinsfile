pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                checkout scm
            }
        }
        stage('Execute Bash Script') {
            steps {
                sh './list_files.sh'
            }
        }
    }
}
