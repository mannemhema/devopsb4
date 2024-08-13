pipeline{
    agent any 
    environment {
        course ="k8s"
        name ="hema"
    }
    stages{
        stage ('first build'){
            environment {
                course ="gcp"
                name ="latha"
            }
            steps{
                echo "my first build $course"
            }
        }
        stage ('second'){
            steps{
                echo "scan sample one $name"
            }
        }
    }
    
}
