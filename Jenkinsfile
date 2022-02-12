pipeline {

agent {

  label 'buildserver'

}
stages {

stage ('Checkout') 
{
steps
    {
    
        checkout scm
        
    }
    
}
stage ('removing testfile')
  {
    steps 
    {
      sh 'cd /home/ubuntu/workspace/pipeline-job ; sudo rm -rf test'
      
    }
  }

}

}
