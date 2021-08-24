pipeline {
    stages {
        stage('clone') {
            steps {
                git 'https://github.com/labbenhatem1995/jenkins-helloworld.git'
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
