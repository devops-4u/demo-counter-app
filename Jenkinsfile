pipeline{

    agent any

    stages{

        stage('Git checkout'){

            steps{
                git branch: 'main', url: 'https://github.com/devops-4u/demo-counter-app.git'
            }
        }
    }
}