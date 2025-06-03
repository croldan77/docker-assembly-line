pipeline {
  agent { docker "maven" }

  stages {
    stage('maven') {
      environment {
            JAVA_HOME = "/usr/lib/jvm/java-17-openjdk/"
        }
      steps {
        sh "mvn -version"
        sh "java -version"
      }
    }
  }
}
