pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building"
                bat 'java -version'
                bat 'javac HelloWorld.java'
                bat 'g++ CppHelloWorld.cpp'
            }
        }
        stage('Run') {
            steps {
                echo "Running"
                bat 'java HelloWorld'
                bat './a.exe'
            }
        }
    }
}
