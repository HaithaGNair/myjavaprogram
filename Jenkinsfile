pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/HaithaGNair/myjavaprogram.git'
            }
        }

        stage('Compile') {
            steps {
                bat 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Hello'
            }
        }
    }
}
