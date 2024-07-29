pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout code from SCM (e.g., Git)
                git 'https://github.com/yourusername/your-repo.git'
            }
        }
        stage('Compile') {
            steps {
                script {
                    // Compile the Java program
                    sh 'javac Add.java'
                }
            }
        }
        stage('Run') {
            steps {
                script {
                    // Run the Java program
                    sh 'java Add'
                }
            }
        }
    }
}
