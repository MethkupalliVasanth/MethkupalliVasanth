pipeline {
  agent any
  stages {
    stage('Dockerizing') {
      steps {
        git(url: 'https://github.com/airavata-courses/MethkupalliVasanth', branch: 'Assignment-2')
        sh '''cd Assignment-2/node-js-orchestrator/


| ./run.sh'''
      }
    }
  }
}