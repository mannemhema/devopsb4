pipeline{
    agent any 
    stages{
        stage ('first build'){
            environment{
                GITHUB_CREDENTIALS = credentials('github')
            }
            steps{
                echo "creds added ${GITHUB_CREDENTIALS}"
                echo "UserId is ${GITHUB_CREDENTIALS_USR}"
                echo "password is ${GITHUB_CREDENTIALS_PSW}"
            }

        }
    }    
}
