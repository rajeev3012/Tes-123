pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo 'Building the project'
            }
        }
        stage('Test'){
            when{
                branch 'feature2'
            }
            steps{
                echo 'Testing the project'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploying the project'
            }
        }
    }
}

