
pipeline{
    agent any
    
    stages{
        stage("Publish mark down to Confluene"){
            steps{
                echo "The build number is ${env.BUILD_NUMBER}"
                echo "You can also use \${BUILD_NUMBER} -> ${BUILD_NUMBER}"                                                
            }
        }
    }
}
