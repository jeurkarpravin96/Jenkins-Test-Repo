pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                javac HelloWorld.java
            }
        }
        stage('Run') {
            steps {
                java HelloWorld
            }
        }
    }
}
