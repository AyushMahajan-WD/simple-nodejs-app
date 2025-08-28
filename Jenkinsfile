pipeline{
    agent any
    stages{
        stage(install){
            steps{
                sh 'sudo apt install npm'
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
