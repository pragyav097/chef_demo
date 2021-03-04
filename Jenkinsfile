pipeline {
  agent any
  stages {
    stage('download profile')
      {
        git url: 'https://github.com/pragyav097/chef_inspec_demo.git'
      }
      stage('run profile')
      {
        inspec exec chef_inspec
      }
  }

}
