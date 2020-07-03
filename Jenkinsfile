pipeline {
  agent any
  environment {
    PATH = "C:/Users/637979/AppData/Local/Programs/Python/Python38-32;%PATH%"
  }
  stages {
    stage('build') {
      steps {
        echo "%PATH%"
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
