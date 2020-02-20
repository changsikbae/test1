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
        sh '''git init'''
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
