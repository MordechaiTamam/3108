properties([pipelineTriggers([githubPush()])])

pipeline {
    /* specify nodes for executing */
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('checkout') {
            steps {
                checkout scm
            }
        }
        stage('list files') {
            steps {
                sh 'ls'
            }
        }
    }
}
