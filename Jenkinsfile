pipeline{
    agent any

    stages{
        stage('Git Checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/Prasathdv/demo-counter-app.git'
            }
            
        }
        stage('Unit testing'){
            steps{
                sh 'mvn test'
            }
        }
    }
}