pipeline {
    agent any
    
    stages {
        stage('clone') {
            steps {
               git branch: 'main', credentialsId: '2d6c4f22-efa0-4f30-9229-ea584bcb55ff', url: 'https://github.com/Yasshhhh04/java-pipeline.git'
            }
        }

        stage('compile') {
            steps {
                bat 'javac Hello.java'
            }
        }

        stage('run') {
            steps {
                bat 'javac Hello.java'
            }
        }
    }
}
