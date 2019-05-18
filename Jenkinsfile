pipeline {
  agent {
    node {
      label 'master'
      customWorkspace 'D:\\GIT\\'
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