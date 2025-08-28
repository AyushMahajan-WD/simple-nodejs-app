pipeline{
    agent any
    stages{
        stage(dependency){
            steps{
            sh 'sudo apt update -y'
            sh 'sudo apt install npm -y '
        }
        }
        stage(install){
            steps{
                sh 'npm install'
            }
        }
        stage(deploy){
            steps{
                sh 'nohup npm start'
            }
        }
    }
}
