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
        sh 'git init'
        sh 'cd /etc/nginx/sites-available'
        sh 'sudo git clone https://www.github.com/changsikbae/test1'
        echo 'ok upload'
      }
    }

    stage('deploy') {
      steps {
        sh 'pwd'
        //sh 'sudo git clone https://www.github.com/changsikbae/test1'
        echo 'ok deploy'
      }
    }

  }
}
