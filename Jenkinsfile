pipeline {
    agent any
    
    tools {
        maven 'my_maven'
    }
    
    environment {
        GITNAME = 'binhao22'
        GITMAIL = 'binhao@naver.com'
        GITWEBADD = 'https://github.com/binhao22/sb_code.git'
        GITSSHADD = 'git@github.com:binhao22/sb_code.git'
        GITCREDENTIAL = 'git_cre'
    }
    
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
