pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'cd /etc/nginx/sites-available'
        echo 'ok build'
      }
    }

    stage('upload') {
      steps {
        sh 'git init'
        //sh 'git push https://www.github.com/changsikbae/test1'
        echo 'ok upload'
      }
    }

    stage('deploy') {
      steps {
        sh 'git clone https://www.github.com/changsikbae/test1'
        echo 'ok deploy'
      }
    }

  }
}
