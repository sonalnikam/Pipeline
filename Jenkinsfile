pipeline {
  agent any
  environment {
    PATH = "C:/Users/637979/AppData/Local/Programs/Python/Python38-32;env.PATH"
  }
  stages {
    stage('build') {
      steps {
        echo "My first python build"
        echo "path is %PATH%"
        echo env.PATH
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
