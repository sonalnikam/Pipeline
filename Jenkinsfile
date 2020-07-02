pipeline {
  agent { docker { image 'python:3.7.2' } }
  stages {
    stage('build') {
      steps {
        echo "$env.WORKSPACE"
        sh 'pip install -r $env.WORKSPACE\\requirements.txt'
      }
    }
    stage('test') {
      steps {
        sh 'python $env.WORKSPACE\\test.py'
      }   
    }
  }
}
