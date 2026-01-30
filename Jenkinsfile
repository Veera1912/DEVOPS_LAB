pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch :"main", url: 'https://github.com/Veera1912/DEVOPS_LAB.git'
            }
        }
        stage('build'){
            steps{
                sh 'javac Hello.java'
            }
        }
        stage('run'){
            steps{
                sh 'java Hello'
            }
        }
    }
}
