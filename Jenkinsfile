pipeline{
    //agent any
    agent {  docker { image: 'maven:3.6.3' } }
    stages{
        stage('Build Stage'){
            steps{
                sh 'maven --version'
                echo "Build Stage"
            }
        }
        stage('Integration Test'){
            steps{
                echo 'Integration Test'
            }
        }
    }
    post {
        success {
            echo 'I run when you are success'
        }
    }
}