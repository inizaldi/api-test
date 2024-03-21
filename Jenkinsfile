pipeline {
  agent any
  stages {
    stage('Install Deps') {
      steps {
        sh 'npm install'
      }
    }

    stage('Unit Test') {
      steps {
        sh 'npm run test'
      }
    }

  }
  tools {
    nodejs 'NodeV18'
  }
}