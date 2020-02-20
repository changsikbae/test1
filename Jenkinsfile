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
<<<<<<< HEAD
        sh '''git init
git checkout dev'''
        sh 'git pull origin dev'
=======
        sh 'cd /etc/nginx/sites-available'
        sh '''git init
'''
        sh 'git pull https://www.github.com/changsikbae/test1'
>>>>>>> f35b7d2ca9f8c3b6c797badbfc1c8cf59cf1a77b
        echo 'ok upload'
      }
    }

    stage('deploy') {
      steps {
<<<<<<< HEAD
        echo 'deploy to master'
        sh 'git push origin master'
=======
        sh 'pwd'
>>>>>>> f35b7d2ca9f8c3b6c797badbfc1c8cf59cf1a77b
        echo 'ok deploy'
      }
    }

  }
}