pipeline {
    agent any
    environment {
        env: Test
    }

    stages{
        stage("Greetings to Test"){
            steps{
                sh 'echo "Welcome to $env environment"'
            }
        }
    }
}
