pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '/home/apache-maven-3.6.2/bin/mvn --version'
      }
    }
    stage('test') {
      steps {
        sh 'echo test service 1.'
        sh 'echo test service 2.'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo deploy success'
      }
    }
  }
}
