pipeline {
    agent any
    environment {
        env: "Prod"
    }

    stages{
        stage("Greetings to Prod"){
            steps{
                sh 'echo "Welcome to $env environment"'
            }
        }
    }
}
