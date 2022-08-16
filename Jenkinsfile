pipeline{
    agent any
  
    stages{
        stage("build"){
            steps{
           echo "Buidling the app..."
            }

        }
      
        stage("test"){
       
      steps{
          echo "Testing the app..."
      }
      
     }
       stage("deploy"){
       
      steps{
          echo "Deploying the app..."
      }
      
    }
      
    }   

}pipeline{
    agent any
  
    stages("build"){
      
      steps{
          echo "Buidling the app..."
      }
      
    }
  
     stages("test"){
       
      steps{
           echo "Testing the app..."
      }
      
    }
  
     stages("deploy"){
       
      steps{
          echo "Deploying the app..."
      }
      
    }

}
