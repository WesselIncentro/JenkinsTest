pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        writeFile(file: '**\\deploy\\*.war', text: 'deploy alfresco')
      }
    }
  }
}