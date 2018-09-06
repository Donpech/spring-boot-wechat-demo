pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'test'
      }
    }
    stage('') {
      steps {
        archiveArtifacts(fingerprint: true, artifacts: '**/*')
      }
    }
  }
}