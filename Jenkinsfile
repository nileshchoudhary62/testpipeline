#!/bin/groovy
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                git scm
                sh "
                echo "hello"
                "
                } }
        }
    }
}
