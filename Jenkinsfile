pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
                        steps {
                            script {
                                // Compilation du projet avec Maven
                                sh 'mvn clean install'
                            }
                        }
                    }
    }



}