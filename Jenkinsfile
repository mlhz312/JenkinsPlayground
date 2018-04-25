pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                javac HelloWorld.java
                echo 'Build done'
            }
        }
        stage ('Test') {
            steps {
                java HelloWorld
            }
        }
    }
}