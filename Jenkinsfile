pipeline {
    agent any

    environment {
        JAVA_HOME = "C:\\Program Files\\Eclipse Adoptium\\jdk-17.0.18.8-hotspot"
        PATH = "${JAVA_HOME}\\bin;${env.PATH}"
    }

    tools {
        maven 'Maven'
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
