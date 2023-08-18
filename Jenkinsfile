pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac C:\ProgramData\Jenkins\.jenkins\workspace\git-hub-java-jenkins-files\HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java C:\ProgramData\Jenkins\.jenkins\workspace\git-hub-java-jenkins-files\HelloWorld'
            }
        }
    }
}
