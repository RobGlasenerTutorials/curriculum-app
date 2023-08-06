pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/RobGlasenerTutorials/curriculum-app.git', branch: 'dev')
      }
    }

    stage('log') {
      steps {
        sh 'sh \'ls -la\''
      }
    }

  }
}