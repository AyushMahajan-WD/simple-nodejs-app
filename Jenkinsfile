pipeline{
    agent any
    stages{
        stage(dependency){
            steps{
            sh 'sudo apt update -S Ayush@123'
            sh 'sudo apt install npm -y -S Ayush@123'
        }
        }
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
