pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                echo 'run java hello without extension'
                sh 'java hello.java'
            }
        }
    }
}