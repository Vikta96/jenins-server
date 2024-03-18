pipeline {
    agent any
    stages {
        stage('Git checkout'){
            steps{
                script{
                    git branch: 'main', url: 'https://github.com/Vikta96/jenins-server.git'
                }
            }
        }
    }    
}