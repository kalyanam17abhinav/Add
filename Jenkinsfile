pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                script {
                    // Compile the Java program
                    bat 'javac Add.java'
                }
            }
        }
        stage('Run') {
            steps {
                script {
                    // Run the Java program
                    bat 'java Add'
                }
            }
        }
    }
}
