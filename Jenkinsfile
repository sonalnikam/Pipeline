pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo "My first python build"
        bat 'SET PATH=%PATH%;%PYTHON_PATH%'
        bat 'python --version'
      }
    }
    stage('test') {
      steps {
        echo 'hello'
      }   
    }
  }
}
