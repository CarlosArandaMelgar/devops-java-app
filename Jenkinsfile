@Library('my-shared-library') _

pipeline{
    agent any

    stages{
        stage('Git Checkout'){
            steps{
                    gitCheckout(
                        branch: "main",
                        url: "https://github.com/CarlosArandaMelgar/devops-java-app.git"
                    )
            }
        }
        stage('Unit Test Maven'){
            steps{
                   script{
                        mvnTest()
                   }
            }
        }
    }
}