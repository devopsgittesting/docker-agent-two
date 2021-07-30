pipeline {
  agent {
    docker {
      image 'centos:7 '
      args 'yum install -y httpd'
    }

  }
  stages {
    stage('build') {
      steps {
        sh '''cat /etc/*-release
'''
      }
    }

  }
}