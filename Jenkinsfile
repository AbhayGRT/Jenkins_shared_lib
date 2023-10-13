@Library('my-shared-library') _

pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                script {
                    def customLibrary = new org.example.CustomLibrary()
                    customLibrary.someFunction()
                }
            }
        }
    }
}
