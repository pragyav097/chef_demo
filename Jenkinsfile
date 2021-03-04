pipeline {
  agent any
  stages {
    stage('download profile')
      { steps {
          git url: 'https://github.com/pragyav097/chef_inspec_demo.git'
         }
      }
      stage('run profile')
      { steps {
          script {
              sh(script:'inspec exec chef_inspec')
            }
          
       }
      }
  }

}
