pipeline {
    agent any
    stages {
        stage('mvn compile') {
            steps {
                echo 'compiling'
            }
        }
        stage('mvn Test') {
            steps {
                echo 'testing..'
            }
        }
        stage('mvn install') {
            steps {
                echo 'install'
            }
        }   
        stage('mvn deploy') {
            steps {
                echo 'deploying'
            }
        }
    }
}
