pipeline {
  agent any
  stages {
    stage ('Build'){
      steps {
        echo 'Running build automation! Rambooooo'
        sh './gradew build --no-daemon'
        archiveArtifacts artifacts: 'dist/train-schedule.zip'
      }
    }
  }
  
}
