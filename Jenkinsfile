pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        sh 'ls'
      }
    }
    stage('Build') {
      steps {
        sh 'bundle exec jekyll build'
      }
    }
  }
}