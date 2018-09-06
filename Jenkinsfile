pipeline {
  agent any
  stages {
    stage('init') {
      parallel {
        stage('init') {
          steps {
            echo 'test'
          }
        }
        stage('init2') {
          steps {
            echo 'test2'
          }
        }
      }
    }
    stage('end') {
      steps {
        archiveArtifacts(fingerprint: true, artifacts: '**/*')
      }
    }
  }
}