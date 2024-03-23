pipeline{

    agent any

    stages{
         
        stage('Git Checkout'){
            
            steps{

                script{

                    git branch: 'main', url: 'https://github.com/sam99-9/mrdevops_java_app.git'
                }
            }
        }
    }
}
