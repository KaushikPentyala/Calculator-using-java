pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Compile') {
            steps {
                sh 'javac Calculator.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Calculator'
            }
        }
    }
}
