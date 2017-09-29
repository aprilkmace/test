pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        writeFile(file: 'pipeline_started.txt', text: 'Started!')
      }
    }
  }
}