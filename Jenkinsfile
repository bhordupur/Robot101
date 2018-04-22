pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''
python2.7 demoapp/server.py'''
      }
    }
    stage('Test') {
      steps {
        sh 'echo "Hello World"'
      }
    }
  }
}