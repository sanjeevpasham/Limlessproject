pipeline {
  agent {
    node {
      label 'master'
      customWorkspace 'D:\\GIT\\${env.JOB_NAME}\\'
    }
  }
  stages {
    stage('clone') {
	steps{
      checkout scm
	  }
    }
  }
}