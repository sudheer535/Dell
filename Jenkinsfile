pipeline{
    agent any
    stages{
        stage ('git checkout'){
            steps{
                git credentialsId: 'NewGitHub', url: 'https://github.com/sudheer535/Dell.git'
            }
        }
    }
}
