pipeline{
    agent{
        label 'Linux'
    }
    stages{
        stage ('git checkout'){
            steps{
                git credentialsId: 'NewGitHub', url: 'https://github.com/sudheer535/Dell.git'
            }
        }
    }
}
