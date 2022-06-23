pipeline{
    agent any
    stages{
        stage('Build Stage'){
            steps{
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