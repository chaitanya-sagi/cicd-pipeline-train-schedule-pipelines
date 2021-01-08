pipeline { 
  agent any
  stages {
    stage ('Build') {
      echo 'Running build automation'
      sh './gradlew --no-daemon
      archiveArtifacts artifacts: 'dist/trainSchedule.zip
    }
   }
  }
}
