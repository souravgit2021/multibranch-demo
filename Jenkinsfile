pipeline {
    agent any
    environment {
        env = "Dev"
    }

    stages{
        stage("Greetings to Dev"){
            steps{
                sh 'echo "Welcome to $env environment"'
            }
        }
    }
}
