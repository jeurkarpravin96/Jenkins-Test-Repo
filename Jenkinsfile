pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building"
                bat 'java -version'
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo "Running"
                bat 'java HelloWorld'
            }
        }
    }
}
