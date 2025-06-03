pipeline {
  agent { docker "maven" }

  stages {
    stage('maven') {
      steps {
        sh "echo  $JAVA_HOME"
        sh "mvn -version"
        sh "java -version"
      }
    }
  }
}
