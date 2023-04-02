pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Runiing build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainschedule.zip'
      }
    }
  
  }
}
