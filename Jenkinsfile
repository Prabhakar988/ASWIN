pipeline{

    agent any
    stages{

        stage('git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/Prabhakar988/ASWIN.git'
            }
        }
        stage('UNIT testing'){
            
            steps{
                
                script{
                    
                    sh 'mvn test'
                }
            }
        }
      }
}