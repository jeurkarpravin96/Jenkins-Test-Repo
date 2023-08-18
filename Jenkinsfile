pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building"
                bat 'java -version'
                bat 'javac HelloWorld.java'
                bat 'g++ cplus.cpp'
            }
        }
        stage('Run') {
            steps {
                echo "Running"
                bat 'java HelloWorld'
                bat './a.out'
            }
        }
    }
}
