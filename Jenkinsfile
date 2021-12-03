pipeline {

agent {

  label 'Ansible-server'

}
stages {

stage ('Checkout') 
{
steps
    {
    
        checkout scm
        
    }
    
}

stage ('successfull excution') 
{
steps {
  node (' newnodes') {
    echo "checkout has been done"
  }
  }


}
}

}
