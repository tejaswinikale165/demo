pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'demo', url: 'https://github.com/tejaswinikale165/demo.git'
                }
            }
        }
        stage('UNIT testing'){
            
            steps{
                
                script{
                    
                   
                }
            }
        }
        stage('Integration testing'){
            
            steps{
                
                script{
                    
                    sh 'mvn verify -DskipUnitTests'
                }
            }
        }
        stage('Maven build'){
            
            steps{
                
                script{
                    
                    sh 'mvn clean install'
                }
            }
        }
      
  
     
        }
        
}
