pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac Jenkins-Test-Repo/HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Jenkins-Test-Repo/HelloWorld'
            }
        }
    }
}
