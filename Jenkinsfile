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
        sh '''git init
cd /etc/nginx/site-available'''
        sh 'git pull https://www.github.com/changsikbae/test1'
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