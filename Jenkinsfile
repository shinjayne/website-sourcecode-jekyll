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
        sh '''bundle install
bundle exec jekyll build'''
      }
    }
  }
}