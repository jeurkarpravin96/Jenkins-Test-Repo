pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building"
                sh 'make' 
                archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true 
               // sh 'java -version'
               // sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo "Running"
                //sh 'java HelloWorld'
            }
        }
    }
}
