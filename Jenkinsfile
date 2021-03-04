pipeline {
  agent any
  stages {
    stage ('download chef')
    {   steps{
      
        sh 'https://omnitruck.chef.io/install.sh'
        sh 'sudo bash -s -- -P inspec'
      }
    }
    stage ('download profile')
      { steps {
          echo "hello"
         }
      }
     stage ('run')
      { steps {
          sh 'inspec exec chef_inspec'
          echo "hello.. running"
         }
      }
     
  }

}
