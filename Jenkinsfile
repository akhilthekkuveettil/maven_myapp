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
                sh 'mvn clean'
            }
        }
        stage('install code') {
            steps {
                sh 'mvn install'
            }
        }
        stage('test code') {
            steps {
                sh 'mvn test -f'
            }
        }
        stage('package code') {
            steps {
                sh 'mvn package '
            }
        }
    }
}
