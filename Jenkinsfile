pipeline {
    agent any

    stages {
        stage('Check Files') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Compile') {
            steps {
                sh 'g++ HelloWorld.cpp -o HelloWorld'
            }
        }

        stage('Run') {
            steps {
                sh './HelloWorld'
            }
        }
    }
}
