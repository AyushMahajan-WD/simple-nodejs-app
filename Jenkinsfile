pipeline{
    agent any
    stages{
        stage(install){
            steps{
                sh 'npm install'
            }
        }
        stage(deploy){
            steps{
                sh 'npm start'
            }
        }
    }
}