pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo "My first python build"
        bat 'SET PATH=%PATH%;%PYTHON_PATH%'
        echo env.PATH
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
