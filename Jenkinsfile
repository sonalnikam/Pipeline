pipeline {
  agent any
 environment {
   PATH = $PATH
 //  PATH = "C:/ProgramFiles(x86)/CommonFiles/Oracle/Java/javapath;C:/WINDOWS/system32;C:/WINDOWS;C:/WINDOWS/System32/Wbem;C:/WINDOWS/System32/WindowsPowerShell/v1.0/;C:/WINDOWS/System32/OpenSSH/;C:/ProgramFiles/PuTTY/;C:/Users/A637979/Desktop/software;C:/Python27;C:/Python27/Lib;C:/Python27/Scripts;C:/Users/A637979/Desktop/software/deepsecurity;C:/Users/A637979/Desktop/software/deepsecurity/api;C:/Users/A637979/Desktop/software/deepsecurity/models;C:/ProgramFiles(x86)/Groovy/bin;C:/ProgramFiles/Git/cmd;C:/ProgramFiles/Java/jdk-11.0.2/bin;C:/ProgramFiles/Docker/Docker/resources/bin;C:/ProgramData/DockerDesktop/version-bin;C:/Users/A637979/Desktop/software;C:/ProgramFiles/nodejs/;C:/WINDOWS/system32/config/systemprofile/AppData/Local/Microsoft/WindowsApps;C:/Users/A637979/AppData/Local/Programs/Python/Python38-32"
 }
  stages {
    stage('build') {
      steps {
        echo %PATH%
        echo "My first python build"
        echo "path is %PATH%"
        echo env.PATH
   //     echo 'SET PATH=%PATH%;%PYTHON_PATH%'
   //     echo env.PATH
        bat 'python first.py'
      }
    }
    stage('test') {
      steps {
        echo 'hello'
      }   
    }
  }
}
