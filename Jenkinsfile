pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo "My first python build"
        sh 'SET PATH=%PATH%;%PYTHON_PATH%'
        sh 'python --version'
      }
    }
    stage('test') {
      steps {
        echo 'hello'
      }   
    }
  }
}
