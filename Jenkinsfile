properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/davidoyetayo/ex20.git'
                bat 'dir'
            }
        }
        stage('Good Morning') {
            steps {
                bat 'githubjenkins.py'
            }
        }
    }
}
