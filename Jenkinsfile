pipeline {
    agent any
    tool {
        maven 'my_maven'
    }
    environment {
        GITNAME = 'KIMJINWOOOOO'           #GITHUB 계정
        GITEMAIL = 'jinwoo3307@gmail.com'   #github email
        GITWEBADD = 'https://github.com/KIMJINWOOOOO/sb_code.git'
        GITSSHADD = 'git@github.com:KIMJINWOOOOO/sb_code.git'
        GITCREDENTIAL = 'git_cre'          # 전에 jenkins credential에서 생성했었다.
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