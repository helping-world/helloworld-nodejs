pipeline {
  agent none
  stages {
    stage('test') {
      agent { label 'nodejs-app' }
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
