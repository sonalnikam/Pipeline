pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo "My first python build"
        bat 'SET PATH=%PATH%;%PYTHON_PATH%'
        bat 'python first'
      }
    }
    stage('test') {
      steps {
        echo 'hello'
      }   
    }
  }
}
