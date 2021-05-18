pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello first self maven project'
            }
        }
        stage('clean code') {
            steps {
                sh 'mvn clean -f maven_myapp'
            }
        }
        stage('install code') {
            steps {
                sh 'mvn install -f maven_myapp'
            }
        }
        stage('test code') {
            steps {
                sh 'mvn test -f maven_myapp'
            }
        }
        stage('package code') {
            steps {
                sh 'mvn package -f maven_myapp'
            }
        }
    }
}
