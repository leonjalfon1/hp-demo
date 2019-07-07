pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'echo npm install'
      }
    }
    stage('test') {
      steps {
        sh 'echo npm run test'
      }
    }
    stage('build') {
      steps {
        sh 'echo npm run build'
      }
    }
  }
}
