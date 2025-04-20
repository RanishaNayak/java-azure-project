pipeline {
    agent {label 'java'}
 
    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/Kumarbgm16/java-azure-project.git'
            }
        }
        stage('maven install') {
            steps {
                sh 'sudo apt install maven -y'
                sh 'mvn --version'
            }
        }

    }
}
