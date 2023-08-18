pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'java -version'
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
