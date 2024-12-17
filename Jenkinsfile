pipeline{
    agent any
    stages {
        stage("stage1"){
            steps{
                bat 'ECHO 123 >step1.txt'
            }
        }
        stage("stage2"){
            steps{
                bat 'ECHO 123 >step2.txt'
            }
        }
    }
}