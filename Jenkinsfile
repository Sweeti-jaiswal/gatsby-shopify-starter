pipeline {
  agent any
  tools {nodejs "node"}
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/Sweeti-jaiswal/gatsby-shopify-starter.git'
        bat 'npm install'
      }
    }
  }
}
