pipeline {
    agent any
    stages  {
        stage ('Build'){
            steps {sh 'echo "Building.."'
                   sh 'ls -al'
        }
    }
    stage ('Test'){
        steps{
            sh 'echo "Testing.."'
            sh 'pwd'
            sh 'ls -al'
        }
    }
        stage ('Deploy'){
            steps {
                sh 'cat ./deploy.sh'
                sh 'echo "Deploying.."'
                sh 'mv testfile.txt/tmp'
                sh 'ls -l/tmp'
                }
            }   
        }
}