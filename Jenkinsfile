pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                 git 'https://github.com/r2fneeraj/mjd.git'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
