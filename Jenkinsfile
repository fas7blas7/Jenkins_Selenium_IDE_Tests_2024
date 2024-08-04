pipeline {
    agent any

    stages {
        stage("Checkout code") {
            //checkout the repository
            steps {
                git branch: 'main', url: 'https://github.com/fas7blas7/Jenkins_Selenium_IDE_Tests_2024'
            }
        }
        stage("Setup dot net") {
            //install dot net
        }
        stage("Restore dependencies") {
            //install dependencies
        }
        stage("Build") {
            //build
        }
        stage("Run tests") {
            //run tests
        }
    }
}