pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'welcome to jenkins2'
        sh '''pipeline {
   agent any
   stages {
      stage(\'Say Hello\') {
         steps {
            echo \'Hello World!\'   
            sh \'java -version\'
         }
      }
   }
}'''
        }
      }
    }
  }