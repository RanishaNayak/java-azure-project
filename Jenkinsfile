pipeline {
    agent any
 
    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/Kumarbgm16/java-azure-project.git'
            }
        }
        stage('maven version') {
            steps {
                sh 'mvn --version'
            }
        }

    }
}
