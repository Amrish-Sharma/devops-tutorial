pipeline{
    
    agent any
    stages{
        stage('Test'){
            steps{
                sh 'echo hello world'
            }
        }
        stage('Build'){
            steps{
                sh 'echo This is Build Phase'
            }
        }
        stage('Deployment'){
            steps{
                sh 'echo This is deployment Phase'
            }
        }
    }

}
