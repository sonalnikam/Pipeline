pipeline {
  agent any
  environment {
    PATH = "%PATH%;%PYTHON_PATH"
  }
  stages {
    stage('build') {
      steps {
        echo "My first python build"
        bat "echo path is %PATH%"
   //     echo 'SET PATH=%PATH%;%PYTHON_PATH%'
   //     echo env.PATH
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
