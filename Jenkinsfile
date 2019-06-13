pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        #sh './gradlew build --no-daemon'
        cat /etc/os-release
        archiveArtifacts artifacts: dist/trainSchedule.zip
      }
    }
  }
}
