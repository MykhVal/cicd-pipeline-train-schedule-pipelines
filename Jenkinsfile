  
pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running b a'
         sh './gradlew build --no-demon'
         archiveArtifacts: 'dist/trainSchedule.zip'
        }
     }
   }
}
