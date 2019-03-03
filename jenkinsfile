pipeline{
    agent any
    stages {
        stage('bulid'){
            steps{
               sh "mvn clean" 
            }
            
        }
        stage('Test'){
            steps{
                 echo "mvn test"
            }
           
        }
        stage('Deploy'){
            steps{
                echo "mvn package" 
            }
           
        }
    }
}
