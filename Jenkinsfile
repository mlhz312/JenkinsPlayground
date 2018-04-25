pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                sh 'javac HelloWorld.java'
                echo 'Build done'
            }
        }
        stage ('Test') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}