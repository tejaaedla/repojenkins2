pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'welcome to jenkins2'
        sh 'java -version'
        echo '${TEST_USER}'
      }
    }
  }
  environment {
    TEST_USER = 'test-user'
  }
}