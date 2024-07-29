pipeline {
    agent any

    stages {
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
