pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git(url: 'https://github.com/bhordupur/Robot101.git', branch: 'master', poll: true)
      }
    }
  }
}