pipeline {
    stages {
        stage('clone') {
            steps {
                git 'https://github.com/priximmo/jenkins-helloworld.git'
            }
        }
        stage('Build') {
            steps {
                sh "javac Main.java"
            }
        }
        stage('Run') {
            steps {
                sh "java Main"
            }
        }
    }
}
