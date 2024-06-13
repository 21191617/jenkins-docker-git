pipeline {
    agent any
    stages  {
        stage ('Build'){
            steps {sh "'echo "Building...'"
                   sh 'ls -al'
        }
    }
    stage ('Test'){
        steps{ 
            sh 'echo "Testing...'"
            sh 'pwd'
            sh 'ls -al'
        '}
    
        stage ('Deploy'){
            steps {
                sh 'cat ./deploy.sh'
                sh 'echo 2Deploying...'"
                sh 'mv testfile.txt/tmp'
                sh 'ls -l/tmp'
                }
            }   
        }
    }