pipelines {
  agent any
  stages {
    stage 'Build' {
      steps {
        echo 'running new build'
        sh './gradlew build --daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
       }
     }
  }
}
