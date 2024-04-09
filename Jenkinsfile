pipeline {
  agent any
  stages {
    stage('Initialize') {
      environment {
        STAGE_DIR = 'C:\\DEVOPS\\simplewebapp-master 2\\deployable'
      }
      steps {
        pwd()
        echo '%JAVA_HOME%'
        echo 'cd'
        echo 'env.BRANCH_NAME'
      }
    }

  }
  environment {
    SCRIPT_DIR = '"C:\\DEVOPS\\simplewebapp-master 2\\deployable"'
  }
}