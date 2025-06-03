pipeline {
  agent { docker "maven" }

  stages {
    stage('maven') {
      steps {
        sh "export $JAVA_HOME=/usr/lib/jvm/java-17-openjdk/"
        sh "mvn -version"
        sh "java -version"
      }
    }
  }
}
