pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'ok build'
      }
    }

    stage('upload') {
      steps {
        sh 'cd /etc/nginx/sites-available'
        sh '''git init
git checkout dev'''
        sh 'git pull origin dev'
        echo 'ok upload'
      }
    }

    stage('deploy') {
      steps {
        sh 'pwd'
        echo 'ok deploy'
      }
    }

  }
}