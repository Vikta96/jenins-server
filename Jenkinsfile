@Library('my-shared-library') _

pipeline {
    agent any
    stages {
        stage('Git checkout'){
            steps{
                script{
                    gitcheckout{
                      branch: "main"
                      url: "https://github.com/Vikta96/jenins-server.git"
                    }
                }
            }
        }
    }    
}