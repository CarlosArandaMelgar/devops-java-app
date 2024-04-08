pipeline{
    agent any

    stages{
        stage('Git Checkout'){
            steps{
                script{
                    git branch: 'main', url: 'https://github.com/CarlosArandaMelgar/devops-java-app.git'
                }
            }
        }
    }
}