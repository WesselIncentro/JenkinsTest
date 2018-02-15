pipeline {
  agent any
  stages {
    stage('Check file.') {
      agent any
      steps {
        fileExists '**\\deploy\\*.war'
      }
    }
    stage('File exists') {
      steps {
        echo 'File exist.'
      }
    }
  }
}