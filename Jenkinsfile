pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'devopscsec', url: 'https://github.com/ramprasad960/rp1.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Hello'
            }
        }
    }
}
