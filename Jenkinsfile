pipeline{
    agent any 
    environment {
        course ="k8s"
        name ="hema"
    }
    stages{
        stage ('first build'){
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
