pipeline {
  agent any {
    stages {
      steps ('Build') {
       echo " Running build automation"
       sh 'gradelw build --no-daemon'
       archiveArtifacts artifacts: 'dist/trainSchedule.zip' 
      } 
    }
  }
}
  
