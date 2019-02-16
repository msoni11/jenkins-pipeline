pipeline {
  agent any
  stages {
    stage('Prepare') {
      steps {
        echo 'Starting automated build'
      }
    }
    stage('Setup') {
      steps {
        git(url: 'git@github.com:msoni11/indepth-migration', branch: 'development', credentialsId: 'c0200426-4b9b-4b7a-ac68-ccdba8ec0923', changelog: true)
      }
    }
  }
}