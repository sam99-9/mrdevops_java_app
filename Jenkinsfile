@Library('my-shared-library') _

pipeline{

    agent any

    stages{
         
        stage('Git Checkout'){
            
            steps{
            gitcheckout(
                branch: "main",
                url: "https://github.com/sam99-9/mrdevops_java_app.git"
            )
            }
        }
    }
}
