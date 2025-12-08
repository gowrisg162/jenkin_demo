pipeline{
  agent any

  triggers{
    pollSCM('* * * * *')
  }

  stages{
    
    stage('Checkout'){
      steps{
        git branch:'main', url:'https://github.com/gowrisg162/jenkin_demo'
      }     
    }
    stage('Build'){
      steps{
        echo "Building..."
      }  
    }
    stage('Test'){
      steps{
        echo "Testing..."
      }
    }
  }
}
