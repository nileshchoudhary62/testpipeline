#!/bin/groovy
pipeline {
    agent any

    options {
        buildDiscarder logRotator(numToKeepStr: '30')
        skipDefaultCheckout true
        disableConcurrentBuilds()
    }

    stages {
        stage ('scm') {
            steps {
                script {
                        
                }
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}
