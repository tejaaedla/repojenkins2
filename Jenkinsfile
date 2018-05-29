pipeline {
  agent any
  stages {
    stage('build') {
      environment {
        MY_NAME = 'tejaswi'
      }
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