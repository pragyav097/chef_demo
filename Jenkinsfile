pipeline {
  agent any
  stages {
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
