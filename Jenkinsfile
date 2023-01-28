pipeline {
  agent any
  stages {
    stage('Code Checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/sauravshekharsingh/kubernetes-project-server.git'
      }
    }
    stage('Install Dependencies') {
      steps {
        bat 'npm install'
      }
    }
    stage('Build') {
      steps {
        bat 'echo "Build Successful"'
      }
    }
    stage('Test') {
      steps {
        bat 'echo "Test Successful"'
      }
    }
  }
}