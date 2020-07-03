pipeline {
  agent any
  environment {

    set PATH = "%PATH%;%PYTHON_PATH"
  }
  stages {
    stage('build') {
      steps {
        echo "My first python build"
   //     echo 'SET PATH=%PATH%;%PYTHON_PATH%'
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
