pipeline {
    agent any
    stages {
        stage ('Build') {
            javac HelloWorld.java
            echo 'Build done'
        }
        stage ('Test') {
            java HelloWorld
        }
    }
}