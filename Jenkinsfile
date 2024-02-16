pipeline {
  agent any
  stages {
    stage('check') {
      steps {
        git(url: 'https://github.com/waladevops/walou.git', branch: 'main')
      }
    }

    stage('') {
      steps {
        sh 'ls -la'
      }
    }

  }
}