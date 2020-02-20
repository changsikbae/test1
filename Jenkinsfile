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
git checkout dev'''
        sh 'git pull origin dev'
        echo 'ok upload'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy to master'
        sh 'git push origin master'
        echo 'ok deploy'
      }
    }

  }
}