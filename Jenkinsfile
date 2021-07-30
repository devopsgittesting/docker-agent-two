pipeline {
  agent none
  stages {
    stage('build') {
      agent {
        docker {
          image 'centos:7'
        }

      }
      steps {
        sh 'cat /etc/*-release'
      }
    }

    stage('deploy') {
      agent {
        docker {
          image 'centos:7'
        }

      }
      steps {
        echo 'This is Deploy Stage'
      }
    }

  }
}