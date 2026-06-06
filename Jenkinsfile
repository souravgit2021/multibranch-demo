pipeline {
    agent any
    environment {
        env: main
    }

    stages{
        stage("Greetings to main"){
            steps{
                sh 'echo "Welcome to $env environment"'
            }
        }
    }
}
