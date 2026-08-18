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
                sh 'g++ addition.cpp -o addition'
            }
        }

        stage('Run') {
            steps {
                sh './addition'
            }
        }
    }
}
