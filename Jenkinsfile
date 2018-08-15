pipeline {
agent any
stages {
  stage ('Build') {
  Steps {
    echo 'Running build automation'
    sh './gradlew build --no-daemon'
    archiveArtifacts artifacts: 'dis/traiSchedule.zip'
         }
      }   
}
}
