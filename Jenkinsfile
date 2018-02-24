pipeline {
    agent any
    triggers { pollSCM("H */2 * * *") }
    environment {
        VERSION="1.0.0"
    }
    stages {
        stage("Build") {
            steps {
                sh "echo build"
            }
        }
        stage("Store") {
            steps {
                sh "echo store"
            }
        }
        stage("Deploy") {
            steps {
                sh "echo deploy"
            }
        }
    }
}
