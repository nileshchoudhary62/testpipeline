#!/bin/groovy
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git scm
                sh "
                echo "hello"
                "
            }
        }
    }
}
