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
                sh './bash_script_project/list_files.sh'
            }
        }
    }
}
