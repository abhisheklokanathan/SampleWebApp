pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "This is build $BUILD_NUMBER of demo $BUILD"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}