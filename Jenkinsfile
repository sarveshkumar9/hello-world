pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Blueocean build pipeline'
      }
    }

    stage('Test') {
      steps {
        junit(allowEmptyResults: true, checksName: 'Test', healthScaleFactor: 1, testResults: 'test-results')
      }
    }

  }
}