pipeline {
  agent any
  stages {
    stage('Initialize') {
      environment {
        STAGE_DIR = 'C:\\DEVOPS\\simplewebapp-master 2\\deployable'
      }
      steps {
        pwd()
        echo 'echo "%JAVA_HOME%"'
      }
    }

  }
  environment {
    SCRIPT_DIR = '"C:\\DEVOPS\\simplewebapp-master 2\\deployable"'
  }
}