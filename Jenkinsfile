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
                sh './20216104/list_files.sh'
            }
        }
    }
}
