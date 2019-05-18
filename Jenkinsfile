pipeline {
  agent {
    node {
      label 'master'
      customWorkspace 'D:\GIT\${env.Job}\'
    }
  }
  stages {
    stage('clone') {
      checkout scm
    }
  }
}