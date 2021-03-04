pipeline {
  agent any
  stages {
    stage ('download profile')
      { steps {
          git url: 'https://github.com/pragyav097/chef_inspec_demo.git'
          echo "hello"
         }
      }
     stage ('run')
      { steps {
          inspec exec chef_inspec
          echo "hello.. running"
         }
      }
     
  }

}
